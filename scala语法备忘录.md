### Trait

Scala Trait(特征) 相当于 Java 的接口，实际上它比接口还功能强大。
* 与接口不同的是，它还可以定义属性和方法的实现；
* 一般情况下Scala的类只能够继承单一父类，但是如果是 Trait(特征) 的话就可以继承多个，从结果来看就是实现了多重继承。

### 可见性

* 只有private，编译会生成 getter、setter 方法提供对外访问；
* private[this] 相对 private 更加严格一些，仅仅可以被同一个类的同一个对象访问，编译没有 getter、setter 方法
* scala默认的访问级别是 public

### 伴生对象

在一个源代码文件中同时定义相同名字的 class 和 object 的用法被称为伴生（Companion）。
Class 对象被称为伴生类，它和 Java 中的类是一样的；而 Object 对象是一个单例对象，用于保存一些静态变量或静态方法。

