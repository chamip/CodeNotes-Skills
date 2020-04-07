### CLion环境配置  

2020-4-7 BY chamip

----

​		亲测有效、简单。

​		首先我本来之前学习c语言的时候第一个码代码软件就是Dev C++，我电脑下载了，它自带编译环境，所以在CLion配置环境时直接用它的环境。<!--CLion可以理解为下载时只是一个编辑器，没有编译器，所以要给它配置编译环境-->

​		我们先打开CLion --> File --> Settings --> Build,Execution,Deployment，按照如下配置，其中地址都是Dev C++文件所在的位置（不是快捷方式文件的位置）。Environment,Make,C Compiler,C++ Compiler这四个需要自己手动输入，一般它不会自动检测填入。

Environment路径填入Dev C++的MinGW64路径:

`C:\Program Files (x86)\Dev-Cpp\MinGW64`

Make路径：

`C:\Program Files (x86)\Dev-Cpp\MinGW64\bin\mingw32-make.exe`

C Compiler路径：

`C:\Program Files (x86)\Dev-Cpp\MinGW64\bin\gcc.exe`

C++ Compiler路径：

`C:\Program Files (x86)\Dev-Cpp\MinGW64\bin\g++.exe`

<img src="C:\Users\asus\Desktop\1.png"/>

最后Apply，OK!

![](http://cdn.jsdelivr.net/gh/chamip/CloudImage/img/20200407193029.jpg)

界面出现调试运行图标就行了！

之前学习C语言的时候想用这个软件，网上好多配置方法都不行，`https://www.jianshu.com/p/1aa989808e15`我的这个方法就是从这位博主这儿学到的，记录一下。

