![Python](https://www.python.org/static/img/python-logo@2x.png)
# Linux安装Python3
##### 检测一哈是否安装了Python3(有些发行版的Linux可能自带了Python3，但与我们接下来的安装不冲突)
```sh
echo '检测是否安装Python3' && python3
echo '返回如下即为已安装
Python 3.4.0 (default, Apr 11 2014, 13:05:11) 

[GCC 4.8.2] on linux

Type "help", "copyright", "credits" or "license" for more information.

>>>
```
### 接着下载Python二进制安装包，进入Python[官网python.Org](https://www.python.org)，单击<kbd>download</kbd>，选择Python(CPython)最新版(此时Python最新版位3.9.2{3.9.2的最大改进是以支持中文变量名，后面会提到})，[小编个人推荐使用Python3，因为Python3与Python2之间存在差距，但大多数人更宁愿选择更有前途的Python3]
### 一般下载到的安装包为 <kbd>Python-3.*.*.tgz</kbd>
```sh
 apt-get update && apt upgrade && apt clean && apt-get install tar && echo '解压安装包' && tar -zxvf Python-3.9.1.tgz && cd Python-3.9.1 && chmod +x configure && ./configure && make && make install
```
```sh
echo '检测一哈是否成功' && python3
```
### 如果返回如下即为成功 
```sh
Python 3.9.1 (default, Apr 11 2014, 13:05:11) 

[GCC 4.8.2] on linux

Type "help", "copyright", "credits" or "license" for more information.

>>>
```
# 配置环境变量
```sh
export PATH="$PATH:/usr/local/bin/python"
```
***
### 如果有问题可以及时在 <kbd>Discussions</kbd> 反馈哦
***
[下一节------>>>](https://github.com/jychenger/Python-From-Introduction-to-Mastery/blob/main/day1/Day2.md)
