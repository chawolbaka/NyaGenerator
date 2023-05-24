# NyaGenerator  
  
使用Source Generator编写的一些代码生成器   
   
* NyaGenerator.Equatable  
在对一个类添加Equatable特性后，会根据所有公开的属性来生成重写== != 操作符、GetHashCode、IEquatable的代码    
（如果忽略某个属性可以使用[IgnoreEquality]）  