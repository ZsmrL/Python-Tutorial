# Python-Tutorial
2024Python自学笔记,记录自己学习和成长过程
# #学习python的笔记,教程为B站播放量最高的

[](https://www.bilibili.com/video/BV1wD4y1o7AS?p=12&spm_id_from=pageDriver&vd_source=3c585af81577ea03e04e9fa67f2ffc22)



# 第一章:

## Python  下载和安装

略

编译器和解释器:
静态语言和脚本语言:
ipo编程方法:

## Python 数据类型

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
input函数

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



