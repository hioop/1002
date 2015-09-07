# 服务器端 telnet 通讯json数据实例


*** A屏链接服务器 ***
```json
{"status":1,"reason":"ok","serial":"ceshi001","type":"reg","time":1439628474,"from":"A","to":"","items":[],"token":"123456"}
```

***A屏发送open开门请求给服务器***
```json
{"status":1,"reason":"ok","serial":"ceshi001","type":"open","message_id":"guarda_2","time":1439628540, "from":"A","to":8,"items":[],"token":"123456"}
```

***B屏上线通知服务器 需要重新开启一个telnet客户端 当做B屏***
```json
{"status":1,"reason":"ok","serial":"woshiBping2","type":"online","version":"v1.0","message_id":"guard_18","time":1439628533,"from":"B","to":"66Y6R15530000903","house_id":13,"items":[],"token":"123456"}
```


通讯地址：
```
# telnet 114.215.193.165 9503
```



