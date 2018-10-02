### String pooling/Interning

The basic idea here is that Java saves memory by using the same instances of string. So lets say there is a string "CAT". 
Now this is stored somewhere in heap memory. So whenever there is a string "CAT" it will point to the same object.

Hence it is usually recommended not to use new String()

[This Dzone article explains about the intern() method and this concept](https://dzone.com/articles/string-interning-what-why-and)


### Flyweight design pattern

Suppose it is costly to create a new object, we should use the FlyWeight design pattern to reuse already created objects. String pooling is also an example of Flyweight design pattern.

[this article explains Flyweight design pattern](https://www.journaldev.com/1562/flyweight-design-pattern-java)

