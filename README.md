<h1>蚂蚁矿机自动超频</hi>

简介
=======
大部分蚂蚁BTC矿机需要手动调整频率，而通过网页可以获取到运行温度和当前运行频率，隔一段时间根据矿机温度调整运行频率可以更安全高效的挖BTC<br />
阿瓦隆矿机可以自动超频<br />

使用
=======
使用之前在main()设置如下参数: <br />
需要自动超频的ip地址<br />
```Python
ips = ['192.168.1.101', '192.168.1.101']
```
矿机的用户名(username)和密码(password)<br />
低于这个温度增加频率<br />
```Python
low_temp = 69
```
高于这个温度降低频率<br />
```Python
high_temp = 73
```
调整频率的周期(s) <br />
```Python
term = 3600
```

之后安装python 2<br />
执行<br />
$python oc.py<br />

Address
=======
欢迎用[币信钱包](https://web.bixin.im/webapp/)打赏<br />
BTC: 13iESTcV1sg1xL6ZSvhiE9Wf4GyzU5iRqL