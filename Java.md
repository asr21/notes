#String pooling/Interning

The basic idea here is that Java saves memory by using the same instances of string. So lets say there is a string "CAT". 
Now this is stored somewhere in heap memory. So whenever there is a string "CAT" it will point to the same object.

Hence it is usually recommended not to use new String()

[This Dzone article explains about the intern() method and this concept](https://dzone.com/articles/string-interning-what-why-and)
