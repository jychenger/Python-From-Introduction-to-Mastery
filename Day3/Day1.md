# 第三章 Python变量与函数  
***
## 第一节 Python变量  

### Python变量的类型
###### 变量存储在内存中的值，这就意味着在创建变量时会在内存中开辟一个空间。基于变量的数据类型，解释器会分配指定内存，并决定什么数据可以被存储在内存中。因此，变量可以指定不同的数据类型，这些变量可以存储整数，小数或字符。  
### 变量的赋值
###### Python 中的变量赋值 __不需要__ 像C或Java一样类型声明。  
###### 每个变量在内存中创建，都包括变量的标识，名称和数据这些信息。  
###### 每个变量在使用前都必须赋值，变量赋值以后该变量才会被创建。  
###### 等号 = 用来给变量赋值。等号 = 运算符左边是一个变量名，等号 = 运算符右边是存储在变量中的值。例如：
```python
#!/usr/bin/python
# -*- coding: UTF-8 -*-
# 这里是注释，不会被视为代码扫描
counter = 100 # 赋值整型(int)变量
miles = 1000.0 # 浮点型(float)
name = "John" # 字符串(str)一般为UTF-8编码
print(counter)
print(miles)
print(name)
```
##### 以上会输出
```python
100
1000.0
John
```
### 试试同时赋值
```python
Python 3.9.1 (default, Apr 11 2014, 13:05:11) 

[GCC 4.8.2] on linux

Type "help", "copyright", "credits" or "license" for more information.

>>>a = b = c = 1
>>>print(a,b,c)
1
1
1
```

***

### 标准数据类型
- Numbers（数字）
    - int（有符号整型）
    - long（长整型[也可以代表八进制和十六进制]）
    - float（浮点型）
    - complex（复数）
- String（字符串）
- List（列表）
- Tuple（元组）
- Dictionary（字典）
