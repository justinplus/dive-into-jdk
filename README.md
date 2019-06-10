# Dive into JDK

There is a well-known saying by Niklaus Wirth.
> Algorithms + Data structures = Programs

However, how to "+" these two parts properly is not an esay thing to do, especially when it comes to a specific programming language. 
On the one hand, we want to make the program as efficient as possible, which requires us to choose the suitable algorithms and data structures, to use the underlying API in a appropriate way, to consider the multi-thread scenario and so on.
On the other hand, we also wish to keep the code easy to read and understand.

Just like learning a foreign language, **imitation** is also a good way to master writing good code.
As a Java programmer, we actually start to use JDK as we write the first code piece, but we seldom read or even analyze its source code. 
Java JDK is really a treasure, for example, classes under Java Collection API, Java NIO have both great abstraction and implementation, which is a best resources to learn at hand.

In addition, Interface doesn't tell the whole story, understanding the logic under the hood helps us to do better trade-offs.
So, I named this repository as *Dive into JDK* to record my learnings and questions while diving into the source code of JDK. I'd like to begin with Java Collection API.
