# itchat_nn
春节期间，见到亲戚玩牛牛。遂做了个微信自动回复机器人，可以在微信群里玩牛牛。基于[littlecodersh/ItChat](https://github.com/littlecodersh/ItChat)

## 依赖说明

* python3  
* itchat  
* prettytable  

## 操作说明

运行机器人。使用微信扫码登陆。  
```
python itchat_nn.py
```

如果二维码显示不正确，可以通过传参的方式调整
```
python itchat_nn.py 1
```

默认相当于
```
python itchat_nn.py 2
```

在机器人所在的群中，发送以下指令进行操作。  

### .新建

在当前群里创建游戏。每个群仅可有一局游戏，重复创建会覆盖已有游戏。

### .报名

若当前群里存在游戏，则加入游戏。仅支持2-10人游戏。

### .开始 | .继续 | .发牌

发牌，并展示结果信息。

### .结束

游戏结束。
