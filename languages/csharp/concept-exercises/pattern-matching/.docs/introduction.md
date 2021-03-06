﻿# Introduction

Pattern matching in C# is very useful and recently
has taken a turn to look more like other languages.
Not only can you test for equality you can also check
for what type the pattern is using.  
The use cases for pattern matching are innumerable
but the use-case that comes to mind first is for
building compilers and parsers.
You can use pattern matching with a traditional
if-then statement, a switch statement, or with
the more modern ML/Haskell guard style.
It looks like this:
```c#
var item = input switch 
{
    3 => item += 3,
    _ => 0
}
```
Where item is an int and input is an int.
If you put in 3 you should get back 6 and if
you put in anything else you 
should get back 0.

