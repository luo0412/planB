# [基础]golang-经典语法

- `learngo` @nice
    - https://github.com/inancgumus/learngo
- from_coder_to_expert @nice
    - https://github.com/0voice/from_coder_to_expert
- Go42 @nice
    - Go四十二章经
    - https://github.com/ffhelicopter/Go42
- Go语言圣经中文版 
    - https://github.com/golang-china/gopl-zh

- Go社区的知识图谱 
    - https://github.com/gocn/knowledge

- Go-Questions @nice
  - 从Questions学习Go
  - https://github.com/qcrao/Go-Questions/wiki

![](https://luo0412.oss-cn-hangzhou.aliyuncs.com/static/images/jianshu/mouse.png)

# golang-优缺点

- 为什么要使用 Go 语言？Go 语言的优势在哪里？@digest
    - https://www.zhihu.com/question/21409296/answer/1210793633

```go
// 缺点
Go 代码很快就会变得非常重复

错误处理也会导致重复
if err != nil { return err }
```

# golang-基础

- go语言
    - https://github.com/golang/go
- golang-examples
    - https://github.com/hope-for/golang-examples

---

# golang-下载安装

- @dl <https://golang.org/dl/>

# golang-开发工具 

- LiteIDE 开发工具 
    - <https://sourceforge.net/projects/liteide/files/>

```js
go run test.go // 运行

atom + script插件
// LiteIDE eclipse
```

---

# golang-基础

- @doc 
    - <http://www.yiibai.com/go/>

```go
让构造简单、可靠且高效的软件变得容易

简洁、快速、安全
并行、有趣、开源
内存管理、v数组安全、编译迅速

一门应用于搭载 Web 服务器，
存储集群或类似用途的巨型中央服务器的系统编程语言

高性能分布式系统领域

海量并行的支持  游戏服务端
```

- 语法

```go
// 语言结构
包声名 导入包

fmt 包实现了格式化 IO（输入/输出）

// 变量声名
var a int = 10
var b = 10
c : = 10

var vname1, vname2, vname3 type
vname1, vname2, vname3 = v1, v2, v3

var vname1, vname2, vname3 = v1, v2, v3 //和python很像,不需要显示声明类型，自动推断

vname1, vname2, vname3 := v1, v2, v3 //出现在:=左侧的变量不应该是已经被声明过的，否则会导致编译错误

// 这种因式分解关键字的写法一般用于声明全局变量
var (
    vname1 v_type1
    vname2 v_type2
)

并行赋值也被用于当一个函数返回多个返回值时，
比如这里的 val 和错误 err 是通过调用 Func1 函数同时得到
val, err = Func1(var1)。

// 值类型和引用类型
使用操作符 := 可以高效地创建一个新的变量，
称之为初始化声明。

如果你声明了一个局部变量却没有在相同的代码块中使用它，
同样会得到编译错误
但是全局变量是允许声明但不使用。

// select
```

# golang- 数据类型

```go
// 派生类
a) 指针类型（Pointer）
(b) 数组类型
(c) 结构化类型(struct)
(d) Channel 类型
(e) 函数类型
(f) 切片类型
(g) 接口类型（interface）
(h) Map 类型

Go 也有基于架构的类型，例如：int、uint 和 uintptr。

// iota
特殊常量，可以认为是一个可以被编译器修改的常量。
在每一个const关键字出现时，被重置为0，
然后再下一个const出现之前，
每出现一次iota，其所代表的数字会自动增加1。
```

# golang-函数

```go
Go 语言最少有个 main() 函数。
```

# golang-指针

```go
// Go 空指针
nil 指针也称为空指针。
nil在概念上和
其它语言的null、None、nil、NULL一样，
都指代零值或空值。

if(ptr != nil)     /* ptr 不是空指针 */
if(ptr == nil)    /* ptr 是空指针 */
```

---

# 参考
