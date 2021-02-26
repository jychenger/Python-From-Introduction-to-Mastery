# 我的第一个Python程序 <kbd>hello</kbd>
## 直接在终端运行hello
### Linux系统中打开终端，输入python，再输入print("hello,world!")，即可看到以下回复
### Windows系统打开Python解释器，输入print("hello,world!")  

```python
Python 3.9.1 (default, Apr 11 2014, 13:05:11) 

[GCC 4.8.2] on linux

Type "help", "copyright", "credits" or "license" for more information.

>>>print("hello,world!")
"hello,world"
```
### 运行过程解释 
##### 当Python解释器(>>>)扫描到函数 <kbd>print()</kbd> 时，就开始打印""里面的字符串(不带思考的打印，字符串str，简单的理解为几个字符如"我的名字就是jychenger"就是一个字符串，<kbd>print()</kbd>的默认打印路径为屏幕)
##### Python的内置函数如<kbd>print()</kbd>有很多(后面一定要带英文括号)Python3中print也变成了函数，但在Python2中它为关键字
|    |    | Python内置函数  |    |    |
|----|----|----|----|----|
|abs()|delattr()|hash()|memoryview()|set()|
|all()|dict()|help()|min()|setattr()|
|any()|dir()|hex()|next()|slicea()|
|ascii()|divmod()|id()|object()|sorted()|
|bin()|enumerate()|input()|oct()|staticmethod()|
|bool()|eval()|int()|open()|str()|
|breakpoint()|exec()|isinstance()|ord()|sum()|
|bytearray()|filter()|issubclass()|pow()|super()|
|bytes()|float()|iter()|print()|tuple()|
|callable()|format()|len()|property()|type()|
|chr()|frozenset()|list()|range()|vars()|
|classmethod()|getattr()|locals()|repr()|zip()|
|compile()|globals()|map()|reversed()|__import__()|
|complex()|hasattr()|max()|round()|  |

## 用变量怎么样呢
### Linux系统中打开终端，输入python(小写)，再输入print(message)，即可看到以下回复
### Windows系统打开python解释器，输入print(message)
```python
Python 3.9.1 (default, Apr 11 2014, 13:05:11) 

[GCC 4.8.2] on linux

Type "help", "copyright", "credits" or "license" for more information.

>>>message = "hello，world"
>>>message
hello，world
>>>print(message)
hello，world
```
## 运行过程解释
##### Python终端解释器扫描到<kbd>message</kbd>，认定它不是关键字后，将变量<kbd>message</kbd>赋值为后面的字符串，临时存储起来，但关闭解释器后就没有变量message了，接着扫描到 <kbd>message</kbd>和<kbd>print(message)</kbd>把message打印到屏幕上面  

## Python内置关键字(不带括号哦)
|  |  |  |  |  | Python内置关键字 |  |  |  |  |  |
|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
|and|as|assert|break|class|continue|def|del|elif|else|except|
|finally|for|from|global|if|import|in|is|lambda|nonlocal|not|
|None|or|pass|raise|return|try|True|Flase|yield|while|with|
### 也可以在终端获得关键字哦
```python
Python 3.9.1 (default, Apr 11 2014, 13:05:11) 

[GCC 4.8.2] on linux

Type "help", "copyright", "credits" or "license" for more information.

>>>import keyword
>>>keyword.kwlist()
```
[下一节------------>>>](https://github.com/jychenger/Python-From-Introduction-to-Mastery/blob/main/Day2/Day2.md)
