默认所有课内C语言要求的内容：包括指针、结构体及之前的内容都已经掌握。

由于要学算法，所以每天抽出来学`cpp`的时间很少。

25.4.26
   
   学习了关于“内存四区”内容。了解了 `new` 的用法、返回值、存储位置。掌握了“引用”的使用方法，以及学习到其本质为封装好的指针。

25.4.27  

   学习了常量引用，函数默认参数、占位参数、函数的重载方面的内容，其中我认为常量引用在工程界应该十分重要。明天准备学习C++最核心的部分“类与对象”，开始了解关于多态、继承、封装方面的知识。

25.4.28

   今天学算法的时间稍多，`cpp` 方面学习的会少一些。觉得之前找的视频不太对，于是换了个更加符合 `CS` 专业教学的课程。只学了 `class` 相关的一些属性与行为的内容，然后补了一下函数方面的内联函数。

25.4.29

   学习了构造函数，才知道 `vector` 初始化的方法实际上就是一种可缺省的构造函数，矩阵初始化的函数也是个构造函数。进一步了解了“对象”的概念，进一步地，学习了 `private`，`public`和`protected`，但是没有动手实操过。

25.4.30

   继续在构造函数上下功夫，分为默认构造函数和复制构造函数，后者比较复杂，在大概三种情形下会被调用，其实不难理解，当需要以一个值为母本进行拷贝的时候就会调用，比如说函数中参数的复制，以及从中间变量到返回值的复制。在这基础上，可以知道引用实际上是不会产生复制构造函数的调用的，无论是参数引用还是返回值引用，这一点在对应练习中已经验证过，然而这也是至关重要的一点，这也是为什么复制构造函数的参数必须是引用的形式出现，否则就会触发对象作参数的复制构造函数——其本身的无限调用。说白了，理解复制构造函数何时调用，就是要去理解 `=` 何时被调用，`A a(b)` 与 `A a=b` 实际上是等效的。
