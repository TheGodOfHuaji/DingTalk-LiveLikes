# DingTalk-LiveLikes
Let your teacher receive much more 👍.
## zh-CN
适用于钉钉

通过修改直播间网页文件达到“点一下100w👍”的效果。
这个项目只是帮助生成关键部分的网页文件，至于前置和后置准备步骤，请参考：
1. [原理演示_Coolapk@T崮郅T](https://www.coolapk.com/feed/16746173?shareKey=MGM2YzMyZWFiYjkyNWU2YzU2MjM~&shareUid=1084326&shareFrom=com.coolapk.market_10.0.2)
2. [在钉钉，如何愉快地给老师点赞？| 小白向，可放心食用_Coolapk@wdq0802](https://www.coolapk.com/feed/17121656?shareKey=OWMyMGJjZTFhZjJkNWU2YzU2ZDg~&shareUid=1084326&shareFrom=com.coolapk.market_10.0.2)
3. [如何在钉钉点出1亿的赞？点十下就能有一亿赞，你不来吗？_Bilibili@波西BrackRat](https://www.bilibili.com/video/av95309382/)

感谢酷安老哥 @wdq0802 和 @T崮郅T 提供思路

如何使用？

1. 第一个输入框为点击一次所增加的赞数。该数字需为10的整数倍，且在10000000以内。可以输入数字或Javascript代码。推荐值Math.ceil(10000000\*Math.random())+1，因为随机数看起来更真实。
注意：当该值设置过大后，请勿配合鼠标连点器使用。因为服务器存储点赞数的变量最大值约为21亿，若超过则会变为负数，可能会导致正常观看的人卡退。请酌情使用！！！

2. 第二个输入框为上传点赞数的间隔时间。单位为毫秒，钉钉默认值1e4（即10000），默认修改为1e2（即100）。推荐值1e2（或100）。

3. 第三个输入框为左上角红色气泡显示内容。钉钉默认值“直播中”，默认修改为“帅气的老师正在直播”，可自定义。

4. 输入完成后，先点击Set，然后点击Downlaod。文件会被下载下来，后续内容请参考前面给出的链接中的教程。

5. 无需担心过多的赞会使老师端或学生端卡顿，理论上点赞数对流畅度没有一点影响，卡顿只取决于从服务器刷新赞数的频率！

6. 请仔细阅读以上操作提示，由于不规范操作导致的一切后果自负！
