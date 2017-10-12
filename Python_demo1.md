# Python简介

- Python是一个高层次的结合了解解释性、编译性、互动性和面向对象的脚本语言
# Python特点

- 易于学习：有相对较少的关键字，结构简单，以及一个明确定义的语法。
- 易于阅读：代码定义较清晰
- 易于维护
- 一个广泛的标准库
- 互动模式：可以从终端输入执行代码并获得结果的语言，互动的测试和调动代码的片段
- 可移植：基于其开放源代码的特性
- 可扩展：可以使用C或C++完成部分程序，然后再Python程序中进行调用
- 数据库：提供所有主要的商业数据库的接口
- GUI编程：支持GUI可以创建和移植到许多系统调用
- 可嵌入：可以嵌入到C/C++程序
# Python环境搭建

- Windows平台安装
  - 下载Python安装包：`https://www.python.org/downloads/windows/`
  - 下载后双击安装包，进入Python安装向导，一直点击下一步直到安装完成即可
- 环境变量配置
  - 电脑—属性—高级系统设置—环境变量—配置path变量—将Python所在路径加入path变量中（如：我的是：F:\Python），windows10以下版本路径间要用;隔开
  - win+R打开cmd命令，输入Python查看是否安装成功
- 运行Python
  - 安装Python之后在lib路径下会有自带的IDE，打开运行即可（如我的就是`F:/Python/Lib/idlelib/idle.py）`
  - 打开cmd命令输入Python直接运行
  - 下载IDE（集成开发环境），如：PyCharm，本人暂时还没有进行实际操作，因为所用Python机会不多，暂时用cmd命令或者自带的IDE。大家有兴趣可以自行百度下载：`https://www.jetbrains.com/pycharm/download/`
# Python基础语法  

- 交互式编程：不需要创建脚本文件，是通过Python解释器的交互模式来编写代码。
  - 在window上打开自带的IDE（即`F:/Python/Lib/idlelib/idle.py`），如：![自带IDE截图](photo/1.png)
  - 在Python2.7.14中输入`print "hello,Python!你好"`，点击enter查看效果，如：![效果图](photo/2.png)  
- 脚本式编程：通过脚本参数调用解释器开始执行脚本，直到脚本执行完毕，当脚本执行完成后，解释器不再有效。
  - Python脚本文件以`.py`为扩展名，将代码写到文件中(如：test.py)，如：![效果图](photo/3.png)  
  如果文件中有中文，需要用`# -*- coding: UTF-8 -*-`转为中文编码，不然不能正常输出）
  - 执行`python C:/Users/thinkpad/Desktop/test.py`(备注：Python已配置在环境变量里面，可直接打开cmd命令，输入该命令行)点击enter可查看结果。
  如：![效果图](photo/4.png)  
# Python标识符  

- 在Python中，标识符由字母、数字、下划线组成。  
- 不能以数字开头  
- 标识符区分大小写  
- 以下划线开头的标识符是有特殊意义的  
  - 以单下划线开头`_foo`的代表不能直接访问的属性，需通过类提供的接口进行访问，不能用`from xxx import *`而导入；
  - 以双下划綫开头的`__foo`代表类的私有成员；
  - 以双下划线开头和结尾的`__foo__`代表Python里面特殊方法专用的的标识，如：`__init__()`代表类的构造函数。  
- Python可以同一行显示多条语句，方法是用`;`号隔开。如：  
![效果图](photo/5.png)  
# Python保留字符  

- 保留字不能用作常数或变数，或任何其他标识符名称；  
- 所有Python的保留字字只包含小写字母；  
以下是Python的保留字：![效果图](photo/6.png)





