# [L]布局视图(WebView+Layout)

# 布局

- BaseRecyclerViewAdapterHelper/BRVAH @nice
    - @code <https://github.com/CymChad/BaseRecyclerViewAdapterHelper>
    - Powerful and flexible RecyclerAdapter

- ChipsLayoutManager @old
    - Tag布局
    - https://github.com/BelooS/ChipsLayoutManager

# 布局-升级

- flexbox-layout @nice
    - https://github.com/google/flexbox-layout

```xml
<com.google.android.flexbox.FlexboxLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    app:flexWrap="wrap"
    app:alignItems="stretch"
    app:alignContent="stretch" >

    <TextView
        android:id="@+id/textview1"
        android:layout_width="120dp"
        android:layout_height="80dp"
        app:layout_flexBasisPercent="50%"
        />

    <TextView
        android:id="@+id/textview2"
        android:layout_width="80dp"
        android:layout_height="80dp"
        app:layout_alignSelf="center"
        />

    <TextView
        android:id="@+id/textview3"
        android:layout_width="160dp"
        android:layout_height="80dp"
        app:layout_alignSelf="flex_end"
        />
</com.google.android.flexbox.FlexboxLayout>
```

- vlayout @nice
    - 针对RecyclerView的LayoutManager扩展, 主要提供一整套布局方案和布局间的组件复用的问题
    - https://github.com/alibaba/vlayout

- FlowLayout @old
    - 流式布局
    - https://github.com/hongyangAndroid/FlowLayout

- views-widgets-samples
    - Multiple samples showing the best practices in views-widgets on Android.
    - https://github.com/android/views-widgets-samples
- android-ConstraintLayoutExamples @old
    - https://github.com/googlearchive/android-ConstraintLayoutExamples

# 布局-效果

- ChatKit @nice
    - 聊天布局
    - https://github.com/stfalcon-studio/ChatKit
- AndroidPileLayout
    - 卡片式布局
    - https://github.com/xmuSistone/AndroidPileLayout
- ViewSpreadTranslationController
    - 视图扩散切换控制器
    - https://github.com/zhangke3016/ViewSpreadTranslationController
- overscroll-decor @old
    - 仿IOS回弹效果
    - https://github.com/EverythingMe/overscroll-decor
- ArcLayout
    - 弧形布局
    - https://github.com/ogaclejapan/ArcLayout
- ScalingLayout
    - 缩放布局
    - https://github.com/iammert/ScalingLayout

# 布局优化

- X2C @nice
    - https://github.com/iReaderAndroid/X2C

```java
在编译生成APK期间，将需要翻译的layout翻译生成对应的java文件，
这样对于开发人员来说写布局还是写原来的xml，
但对于程序来说，运行时加载的是对应的java文件
```

# 屏幕适配

- AndroidAutoSize @nice
    - 今日头条屏幕适配方案终极版
    - 一个极低成本的 Android 屏幕适配方案
    - https://github.com/JessYanCoding/AndroidAutoSize

- AndroidScreenAdaptation
    - https://github.com/yatoooon/AndroidScreenAdaptation

# ViewPager

- MaterialViewPager 
    - <https://github.com/florent37/MaterialViewPager>

- VerticalViewPager
    - 垂直
    - https://github.com/castorflex/VerticalViewPager
- InfiniteCycleViewPager
    - https://github.com/Devlight/InfiniteCycleViewPager

# StatusBar 状态栏

- StatusBarUtil @nice
    - https://github.com/laobie/StatusBarUtil
- ImmersionBar @nice
    - https://github.com/gyf-dev/ImmersionBar

# Nav

# Indicator 指示器

- MagicIndicator @nice
    - https://github.com/hackware1993/MagicIndicator

- dotsindicator
    - https://github.com/tommybuonomo/dotsindicator 

- PageIndicatorView
    - https://github.com/romandanylyk/PageIndicatorView

# Menu

- MaterialDrawer
    - https://github.com/mikepenz/MaterialDrawer
- Side-Menu.Android
    - 侧滑菜单
    - https://github.com/Yalantis/Side-Menu.Android
- FlowingDrawer
    - 带手势的侧滑菜单
    - https://github.com/mxn21/FlowingDrawer    
- Context-Menu.Android
    - 上下文菜单
    - https://github.com/Yalantis/Context-Menu.Android
- bottomsheet
    - 底部菜单
    - https://github.com/Flipboard/bottomsheet
- BoomMenu
    - https://github.com/Nightonke/BoomMenu
- SlidingMenu @nice
    - https://github.com/jfeinstein10/SlidingMenu

# Tab

- NavigationTabBar
    - https://github.com/Devlight/NavigationTabBar
- BottomBar @old @nice
    - <https://github.com/roughike/BottomBar>

# WebView

- VasSonic
    - 首屏加载快
    - https://github.com/Tencent/VasSonic
- AgentWeb
    - https://github.com/Justson/AgentWeb

# ScrollView

- Android-ObservableScrollView
    - https://github.com/ksoichiro/Android-ObservableScrollView

# 自定义view

- SmartRefreshLayout @nice
    - 下拉加载
    - <https://github.com/scwang90/SmartRefreshLayout>

- android-Ultra-Pull-To-Refresh @nice
    - Support all the views.
    - https://github.com/liaohuqiu/android-Ultra-Pull-To-Refresh

- Android-PullToRefresh @old
    - https://github.com/chrisbanes/Android-PullToRefresh

- SpringView
    - https://github.com/liaoinstan/SpringView

---

# Banner

- banner @nice
    - https://github.com/youth5201314/banner

- Android-ConvenientBanner
    - 3D effects
    - https://github.com/saiwu-bigkoo/Android-ConvenientBanner

# Guide 新手引导

- NewbieGuide
    - https://github.com/huburt-Hu/NewbieGuide

- GuideView
    - 东半球最好用
    - https://github.com/binIoter/GuideView

---

# Toast

- SuperToasts
    - https://github.com/JohnPersano/SuperToasts    

---

# 路由

- `ARouter` @nice
    - 帮助 Android App 进行组件化改造的路由框架
    - https://github.com/alibaba/ARouter

- DeepLinkDispatch
    - https://github.com/airbnb/DeepLinkDispatch

# 图片加载

- glide @nice
    - <https://github.com/bumptech/glide>

# 预加载

- PreLoader @nice
    - https://github.com/luckybilly/PreLoader

# 延迟

- android-job @nice
    - 后台运行延迟的工作
    - https://github.com/evernote/android-job

---

# 键盘冲突

- JKeyboardPanelSwitch
    - Android键盘面板冲突 布局闪动处理方案
    - https://github.com/Jacksgong/JKeyboardPanelSwitch
