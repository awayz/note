---
title: qq 被风控的解决方案
create_time: 2022-08-04 14:24
modification_time: 2022-08-04 14:24:56
tags:
- mirai
---

使用 go-cqhttp 和 hoshino-bot 搭建的 qq 机器人被腾讯风控了，日志显示 `Protocol -> sendPacket msg error: 46`。 google 之后有以下几种解决方案：
1. 手机登录QQ，在群里发一条消息，如果发不出去然后下面显示了一行点击检测啥的，点进去就可以了
2. 打开设置->账号安全->QQ安全中心->联系客服->账号->QQ功能检测