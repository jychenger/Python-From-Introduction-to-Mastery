![Python](https://www.python.org/static/img/python-logo@2x.png)
# Linux安装Python3
##### 检测一哈是否安装了Python3
```sh
echo '检测是否安装Python3' && python3
echo '返回如下即为已安装
Python 3.4.0 (default, Apr 11 2014, 13:05:11) 

[GCC 4.8.2] on linux

Type "help", "copyright", "credits" or "license" for more information.

>>>
```
### 接着下载Python二进制安装包，进入Python[官网](https://www.python.org)，单击<kbd>download</kbd>，选择Python(CPython)最新版(此时Python最新版位3.9.1)，[小编个人推荐使用Python3]
### 一般下载到的安装包为 <kbd>Python-3.*.*.tgz</kbd>
```sh
apt-get install tar && echo '解压安装包' && tar -zxvf Python-3.9.1.tgz && cd Python-3.9.1 && chmod +x configure && ./configure && make && make install
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
