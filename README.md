# Learn Kotlin
[马上开学](https://github.com/kaixueio)的学习笔记

## 基础
### 基本语法
- 基本要素
- 流程语句
- 异常的处理

### 函数
- 函数的定义和拓展函数，拓展属性
- 可变参数，中缀调用，字符串，正则表达式的处理
- 局部函数和拓展

### 类，对象和接口
- 类的定义，继承（要说说 修饰符比如 open ，内部类，嵌套类，密封类，数据类等等）
- 类和属性（说说类的主从构造方法，资源的初始化流程，还能讲讲 Kotlin 中的幕后字段，重写 get set，和访问器的可见性。还要说说 static 跑哪里去了）
- 委托类（by 关键词）
- 委托属性
- object 的用法（对象声明，伴生对象，对象表达式等等）

### 类型系统
- 可空性（一定要说到的点：含义，解决的问题，怎么安全的调用 ?. 安全转换 as? 非空断言!! let 和 ?.let 延迟初始化 可空的拓展函数 和 Java 之间调用怎么保证可空的安全性）
- 基本类型进阶（进阶说说基本类型，数字转换，可空的基本类型，Any Any? Unit 和 Java 的 void 和 Nothing）
- 集合与数组（集合，和可空集合，只读和可变集合，Koltin 集合和 Java 的一些关系，集合的操作符和序列等等,数组和 Java 的数组）

## 进阶
### Lambda
- 基本表达式，和引用
- lambda 和 java 直接的互相使用（可以说一下 Java 中可以用 this 拿到自己，lambda却不可以：比如在 Listener 里面 Java 可以 用 this 取消自己，Kotlin 不行）
- 带接受者的 lambda （with apply等等，说说这些函数的实现原理）
- 高阶函数（高阶函数的定义，Java 中怎么调用）
- 内联函数
- 高阶函数中的return

### 重载运算符
- 重载各式各样的运算符
- 集合和区间（in range get set）
- 解构声明

### 泛型（重中之重：一定要把 in out 讲清楚）
- 泛型的基本使用和声明
- 泛型的约束（super 和 extend 在kotlin中的一些类比）
- 泛型的空和非空
- 运行时的泛型（这个比较复杂：说说泛型擦除，Kotlin 中泛型的判断比如 is T as T 是怎么通过内联实现的 还有 T::class ）
- 泛型的子类型化（协变 逆变 把 in out 和 ？ Extend 和 ？ super 结合起来说一说：这个比较绕 也很考验作者的功底，还得讲一下 * 符号 在泛型中的使用）

### 注解，反射
- 申明和应用注解（元注解，泛型，用于java的注解 @jvmstatic 等等）
- 反射（说说反射 Api KClass KCallable KFunction KProperty 等等）

### DSL 
- 什么是 DSL
- DSL 的定义

## Kotlin 1.3
- 协程（只用说协程本身的东西，不用讲和 Android 的配合，配合使用在后面的章节）
- 契约（这一节比较简单 ，可以和内联类一起写）
- 内联类

## Kotlin 和 Android
### Kotlin 在 Android 中的运用
- Android 和 Kotlin 拓展库（介绍下 Koltin 专门为 Android 编写的拓展库比如：不用自己写 findById 的 extension ，KTX ，Anko 等等。）
- Kotlin 和 Android （结合之前的文章，说一说 Koltin 在 Android 中的实践 用一些项目中的例子来体现 Kotlin 开发 Android 的真正便利，比如说：拓展方法，let，apply lazy 等在 Android 中实际应用）

### Unit test
- Kotlin 单元测试（讲解 Kotlin 在 单元测试的应用，介绍一些专门为 Koltin 设计的 单元测试库）

### 协程和 Android
- Kotlin 单元测试（讲解 Kotlin 在 单元测试的应用，介绍一些专门为 Koltin 设计的 单元测试库）


