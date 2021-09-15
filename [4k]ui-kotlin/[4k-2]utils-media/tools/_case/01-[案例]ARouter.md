# [案例]ARouter

- @code https://github.com/alibaba/ARouter

```java
@Route(path = "/test/activity")
public class Test1Activity extends Activity {
    @Autowired
    public String name;
    @Autowired
    int age;
    @Autowired(name = "girl") // Map different parameters in the URL by name
    boolean boy;
    @Autowired
    TestObj obj;    // Support for parsing custom objects, using json pass in URL

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        ARouter.getInstance().inject(this);

        // ARouter will automatically set value of fields
        Log.d("param", name + age + boy);
    }
}
```