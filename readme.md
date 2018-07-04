[![chatoper banner][co-banner-image]][co-url]

[co-banner-image]: https://user-images.githubusercontent.com/3538629/42217321-3d5e44f6-7ef7-11e8-94e7-1574bfa1dbb8.png
[co-url]: https://www.chatopera.com

```
========dgk_lost_conv========

chinese conversation corpus

可以用作聊天机器人的训练语料

```



您好，很多想要学习制作聊天机器人的朋友都会找到这里，我觉得有必要给大家建立一个简单的交流场所，于是我建立一个QQ群。欢迎加入讨论：

![](qun.png)

```


结果：

dgk_shooter_z.conv 110MB 已分词

dgk_shooter_min.conv 按字分词

lost.conv 1.7MB

fanzxl.conv 2.3MB

fk24.conv 4.5MB

haosys.conv 1.3MB

juemds.conv 793KB

laoyj.conv 1.5MB

prisonb.conv 543KB

内部方法：

asstosrt -s utf-8

ass ----asstosrt---->srt

srt ----cvgen.py---->.conv

特别的shooter73g:

进入shooterwp，

解压缩mirror.x到rawbase下面

执行sel.sh

在跟目录下

fixcodec修正编码

fixtranc繁简处理

genall

.conv 格式:

//M 表示话语，E 表示分割。

E

M 话语 a

M 话语 b

M 话语 c

M 话语 d

E

M 话语 a

M 话语 b

M 话语 c

M 话语 d

License:

MIT

```

