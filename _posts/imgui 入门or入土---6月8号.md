# imgui 入门or入土

现在也叫做 dear imgui了,因为之前imgui在之前就有人已经提出了，imgui = immediate mode graphical user interface 即时模式的图形用户接口，为了加以区分。



## what

imgui是一个C++图形用户界面库，它的应用非常多，主要是用来创造一些图形工具，以此来方便自己的工作。

大神们利用imgui完成的作品(https://github.com/ocornut/imgui/issues/123)

## why

为什么要使用imgui呢，额，公司要求，哈哈，其实看了一眼imgui的readme的usage，上面列出很多imgui的功能的介绍。但是尚未使用，自身没有多大的体会，有一点我倒是看出来了，在usage有一条写的是这个库很独立（ **self-contained**），的确实这样，因为这个库有很多demo这些demo支持各种图形api像OpenGL，direct，还有vulken。

## how

那么现在最大的问题来了，如何学习它，并且能够熟练的使用它来制作自己想要的ui界面

我们把目光收回来一点，我现在的任务是制作一个用户界面，也可以说是一个软件了，它能够解析json文件，将其变为树状结构，并在图形界面上显示出来，并且我们在操作用户界面是还可以实现json数据的修改。难度可以说是相当的大。我现在的第一步就是熟悉imgui，虽然看网上人说imgui多么多么简单，多么容易之类，但我从未接触过这类库。还是需要好好学习以下的。