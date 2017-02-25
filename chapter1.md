#第一章 Scala语言简介


Scala正如其名，一门可扩展的语言，它就是一个含有精美工具的工具箱，里面有静态类型, OOP, FP, 宏等工具。马丁的书上说，

> Scala不是在单纯的混合面向对象和函数式，它是一门可被无限扩展的语言，每次添加新特性都是在丰富工具箱。

所以有人说Scala太复杂了，也有人说Scala满足了我对编程语言的所有幻想。


##### 两个教程：

1.ScalaTutorial：
http://www.scala-lang.org/docu/files/ScalaTutorial.pdf

2.ScalaByExample：
http://www.scala-lang.org/docu/files/ScalaByExample.pdf


## 1 第一个例子:HelloWorld!

```scala
/**
  * Created by jack on 2017/2/25.
  */
object HelloWorld {
  def main(args:Array[String])={
    println("Hello World!")
  }

}

```
