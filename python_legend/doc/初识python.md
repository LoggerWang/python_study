#初识Python
- 3月都快结束了，又到了万物交配的季节！是时候执行今年的计划之一了，再学一门语言，那就python吧！好记性不如烂笔头，还是把学习的东西记录一下，以便加深印象和后面翻阅

## 一、什么是Python[（官网）](https://www.python.org/)
- Python是人称龟叔的Guido va Rossum在1989编写的一门高级编程语言。python有很完善的内置基础代码库，包括网络、文件GUI、数据库、文本等，所以在python开始有许多功能不必去重复造轮子。另外还有大量的第三方库可以拿来使用。
- 据说现在很多网内外的主流网站都是用python开发的，具体哪些网站我也没法去验证，不过个人感觉python还是挺牛逼的。
## 二、Python的优缺点
- 优点：优雅、明确、简单、易读，对初学者入门门槛低，代码量少。
- 缺点：python是解释型语言，代码在执行的时候需要逐行翻译成CPU需要的机器码，比较耗时，所以运行速度相对C比较慢。另外一个缺点就是解释型的语言都不能加密，发布出去的代码都是源代码，
- python的应用场景：网站、后台、脚本等
- 环境搭建：下载[Windows64位Python3.5](https://www.python.org/ftp/python/3.5.2/python-3.5.2-amd64.exe)或[32位Python3.5](https://www.python.org/ftp/python/3.5.2/python-3.5.2.exe)后添加到环境变量，环境配置好之后，运行cmd,输入python，如果显示有Pyhton 3.5.X就是配置成功，否则就是环境变量没有配好，需要重新配置。

## 三、Python解释器
- python写的代码是已.py结尾的文件，有多重python解释器。
- CPython:应用最广泛，官网下载安装的python3.5就能获取到一个官方版本的python解释器，也就是CPython,顾名思义CPython就是用用C语言开发的python解释器，它以>>>作为提示符
- 当然还有其他解释器，如IPython是在CPython之上的一个交互式解释器，相比增强了交互方式，但是执行代码的功能和CPython是一样的，还有Pypy、Jython、IronPython等解释器类型。如果要和Java或.Net平台交互，最好的办法不是用Jython或IronPython，而是通过网络调用来交互，确保各程序之间的独立性。
-
## 四、HelloWorld
- 每学一门开发语言都是从HelloWorld入手的，Python的hellowrold是这样的：在dos窗口下的命令行输入python,进入到python交互式窗口，这时有>>>的提示符，输入：

```
printf('hello,world')
```
然后就有hello,world输出了，就是这么简单。如果在>>>后面输入1+2，回车，会输出结果3

- 除了直接在python交互环境下输入python代码之外，还可以运行一个.py的文件去执行文件里的python代码，比如，在命令行模式下执行：

```
C:\work>python calc.py
```
解释器就会代码执行python calc.py里的代码
- 退出python交互环境：exit()


## 五、Pyhton编辑器

推荐两种编辑器,但绝对不能用word和记事本，因为word保存的不是纯文本文件，记事本不知道是啥原因，可能是编码的问题吧
- [Sublime Text](http://www.sublimetext.com/)
- [Notepd++](http://notepad-plus-plus.org/)

比如在D: /python文件下创建helloworld.py文件
里面输入：

```
print('helloworld from notepad')
```
然后到命令行进入到相应文件夹下下输入
python helloworld.py,则会输出 helloworld from notepad.
* 文件名只能是英文字母、数字和下划线的组合
* 如果在windows中想直接点击运行python文件，需要在.py文件的第一行加上特殊注释：

```
#！/usr/bin/env python3
print('helloworld from nodepad')
```

## 六、输入和输出

- 输出：print()函数
执行 print('helloworld'),则输出：

```
helloworld
```
执行：
print(1+2)则输出：

```
3
```
执行：
print('1+2='，1+2)则输出：

```
1+2=3
```
print里面的‘1+2=‘会被当做字符串输出，后面的1+2会被直接执行计算结果

- 输入：input()函数
执行：

```
>>> name = input()
```
交互环境则进入用户输入等待状态，用户输入Legend,点击回车后，则吧Legend的值赋值给了name,再输入name回车，则会输出name的值：Legend

```
>>> name
'Legend'
```
## 总结：

感觉还挺有意思的，和Java、C是不同，但是具体还得往后面看看。总算开了个头，后面好好坚持吧！前戏结束了，该切入正题了，好激动。

