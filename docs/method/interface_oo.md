golang中没有面向对象，但却可以实现面向对象的基础功能，类比如下：

- 基类：golang中的接口相当于面向对象中的基类（虽然接口并不完全是基类的概念，但在某些情况下，会把接口当作基类来使用），只不过继承基类需要显式，而golang的接口是隐式，并且只是方法名和传入传出参数相同即可

- 类：golang中的struct相当于面向对象中的类

- 类的属性：golang中struct的元素相当于面向对象中类的属性

- 类的方法：golang中struct的方法（就叫method，在某些语言里叫签名函数）相当于面向中的类的方法

例子详见[比较python和go的面向对象写法](/golang/method/overview/#pythongo)
