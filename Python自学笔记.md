# #学习python的笔记,教程为B站播放量最高的

[](https://www.bilibili.com/video/BV1wD4y1o7AS?p=12&spm_id_from=pageDriver&vd_source=3c585af81577ea03e04e9fa67f2ffc22)



# 第一章:

## Python  下载和安装

略

编译器和解释器:
静态语言和脚本语言:
ipo编程方法:

## python 基本函数
print函数
ASCII码:chr

```python
print('b')
print(chr(98))

print(ord('北'))
print(ord('京'))

```
open:
```python
fp = open('note.txt','w')
print('没有毅力是不可能成功的',file = fp)
fp.close()
```
reload in  gbk/.....     #用什么编码重新加载

![[Pasted image 20240107121333.png]]
```python
print('北京',end='-->')
print('欢迎你') #修改了换行符,在同一行输出,但下一个print还是有换行符
```
字符串连接:字符串和字符串之间的连接
input函数:

## 数字型
1. int 
2. bool
3. float
4. compelx

## 字符串型 

# 第二章:

## 关键字和保留字:严格区分大小写

```python
import keyword
print(keyword.kwlist)
print(len(keyword.kwlist))
```

## 变量和常量

type:数据类型

id方法:查询变量的内存地址

python中所有字母都大写就为常量,共识的

```python
pi = 3.1415926 #定义了一个变量
PI = 3.1415926 #定义了一个常量
```

## Python 数据类型 

### 整数型:

四种进制:2.8.10.16

### 浮点型:

​	浮点数相加:会出现不确定的尾数问题

```python
print(0.1+0.2)
print(round(0.1+0.2,1)) # 保留一位小数
```

### 复数类型:实部+虚部

![image-20240109003923151](C:\Users\Administrator.DESKTOP-164C7EH\AppData\Roaming\Typora\typora-user-images\image-20240109003923151.png)

### 字符串型:

'''用于多行字符串

\t一个制表位为8个字符

正向索引:0-9 逆向索引:-10- -1 

```python
print(s[2:7])#切片操作  从二开始到7结束不包含7
print(s[-8:-3])#反向递减
print(s[:5])#默认N从0开始
print(s[5:])#默认M是字符串的结尾

print(s[2:7])#切片操作  从二开始到7结束
```

![image-20240111002741750](C:\Users\Administrator.DESKTOP-164C7EH\AppData\Roaming\Typora\typora-user-images\image-20240111002741750.png)

+:字符串拼接

*:字符串复制

in:字符串查找

### 布尔类型

Ture表示整数1,False表示整数0

```python
print(bool(18)) #非零的证书的布尔值都是true
print(bool(0),bool(0.0))
print(bool("HeLLO WORLD"))#非空字符串的bool值都是true
print(bool(''))
print(bool(False))#False
print(bool(None))#False
```

![image-20240111011618742](C:\Users\Administrator.DESKTOP-164C7EH\AppData\Roaming\Typora\typora-user-images\image-20240111011618742.png)

## 数据类型转换
