# python 查询12306火车票
## 前言
>12306 的接口经常变化，内容可能很快过期，如果遇到接口问题，需要根据最新的接口对代码进行适当修改才可以完成实验。
[**`实验楼课程链接`**](https://www.shiyanlou.com/courses/623) [`b站视频`](https://www.bilibili.com/video/av12380578?from=search&seid=447551889627754451) [`官方git`](https://github.com/protream/tickets)
---
![](http://i1.bvimg.com/643282/949062d7aec8543e.jpg)

## 需要用到的库
```
$ pip3.5 install requests colorama docopt prettytble  
```
- `docopt` -> 命令行解释器
- `requests` -> 文本着色器
- `colorama` -> http请求库
- `prettytable` -> 表格显示及美化

## 接口设计
用户输入的信息包括出发站，到达站、日期以及火车类型，这几个选项应该能被组合使用：  
```
$ python tickets.py [-gdtkz] from to date
```
## 代码实现
[**codes**](https://github.com/Monotone1997/my-python-projects/blob/master/train%20tickets/tic.py)
