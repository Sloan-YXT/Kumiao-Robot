# Kumiao Robot

代Kumiao Robot于GitHub开源|官网为http://www.kumbot.cn/


日期：2020年10月7日

版本：KuMiao QQrobot Ver 1.0.0（酷喵机器人_Kumbot）

官方Q群：1135595556

官网地址：www.kumbot.cn

（酷喵QQ机器人持续维护更新，酷喵VX机器人开发ing）

开源代码类型：易语言

（招募LOGO设计者QWQ）

======================强烈建议您认真看完本文档==================



推荐懂易语言的开发者不必要修改本框架源码后另起炉灶

直接以KumQQrobot为框架开发插件是最好的选择~（目前官方社区在建设中~官网www.kumbot.cn）

同时我们欢迎各开发者加入官方开发团队来一起优化更新框架，感谢您的支持，前路未定，一切皆有可能！



使用说明：

（需要用到语音/分享音乐/群礼物的功能就得运行go-cqhttp，不用到的可以单独运行框架程序）

1.在框架文件中 以记事本的方式打开config.json文件

"uin": 123456789,

"password": "qq123456789",

以此方式将 账号 密码填入后保存，关闭即可

2.运行go-cqhttp.exe文件（会自动登录）（2,3步骤顺序随意）

3.运行框架主程序 KumQQbot.exe（手动/扫码登录）（2,3步骤顺序随意）



（登录不上请关闭设备锁，或者在本机上登录，常用IP号登录是最稳妥的）

（框架本身可用扫描二维码登录，这个应该能有效解决账号密码登录的问题）

（时不时关注go-cqhttp.exe内显示的内容或许对你有帮助，登录时如果需要输入验证码或者是登录验证，会生成验证码图片在框架文件内，自行查看后输入验证码回车登录，登录验证是一般是生成一个http链接，复制访问，即可用手机进行登录验证）


======================强烈建议您认真看完本文档==================

开发工作计划：

1.持续维护，尽量修复原框架内协议的api功能

2.持续更新，利用MGCH（MiraiGO-CQhttp）的api功能进行弥补（或 MGCH化，脱离原框架）

3.更多优化，细节处理

4.VX框架开发（免费，不开源，已hook基本功能，正在开发插件处理系统和设计UI）



======================强烈建议您认真看完本文档==================

框架更新日志：

======================强烈建议您认真看完本文档==================

KuMiao QQrobot 1.0.0（2020-10-7 22:00 酷喵机器人_Kumbot）

更新内容：



1.框架改名 MQ==>Kum （QQrobot开源上线，VXrobot开发ing）

2.插件编译后命名规则为：XXXX.kum.dll    XXXX需对应插件开发模板中的 插件名称

3.结合MGCH（MiraiGO-CQhttp）弥补劣势，框架改为单Q登录

4.新增MGCH的调用api：发送好友/群聊消息 上传图片/语音/视频  分享音乐/群免费礼物

5.其他小细节小BUG维护修复

======================

MQ Bate 0.0.3（2020-10-6 22:45）

更新内容：



新增若干BUG

======================

MQ Bate 0.0.2（2020-10-4 16:42）

更新内容：



新增若干BUG

======================

MQ Bate 0.0.1（2020-10-3 11:47)

更新内容：


新增若干BUG


======================下面是更多说明告示==================





更多说明告示（摘自官方群公告/自行补充）：

框架自带协议:pc911,tim3.1,企业,企点

miraigo-cqhttp（以下简称MGCH）

所带协议： 安卓平板，安卓手机，手表

框架不签订AGPL协议但遵守MGCH的AGPL协议，所以开源任何东西包括本身框架协议以及调用MGCH的程序

用户可选择成品使用，开发者可根据SDK开发插件或利用程序源码帮忙维护升级优化本框架程序（Kumiaorobot，简称Kumbot）

本框架基于PC911的api功能较多的一个协议，但有存在细节和BUG问题，故此我突发奇想，利用MGCH来弥补api功能的缺失，日后的维护更新可能会逐渐使本框架脱离原来的PC协议，逐渐"MGCH化"，大佬不喜勿喷

感谢各位的关心支持，使用本框架以及相关程序的源码进行修改，请保留原版版权地址和MGCH/Mirai的Github版权地址，并且不支持不鼓励进行商业/非法活动，所造成一切后果请您自行承担，与本作者/MGCH/Mirai无关！



1.有人说开源发出去不就烂大街和谐了吗（PC911几乎人手一份），鄙人认为PC协议不是很容易就和谐，如果api和谐，我们的MGCH化工作会加快，不必担心

2.本框架主体使用PC911（比网传9P版本多部分API）并且独立开发了SDK，插件管理，UI方面仿制未闻花名的UI，按钮图片是重新PS过的，期间多方求助各种大佬，也算付出了点心血吧

3.感谢各位大佬的帮助，为框架主体源码方面提供优化处理（如api功能修复，TIM3.1登录协议等）



Mirai项目地址https://github.com/mamoe/mirai

MiraiGO-CQhttp项目地址https://github.com/Mrs4s/go-cqhttp

KumiaoQQrobot项目地址：http://kumbot.cn/（官网下载源码）




酷喵VX机器人开发进度（免费，不开源，并且将作为主要框架）

1.已完成基本事件功能的收发（相对于QQ框架稳定轻盈全面）

2.正在开发插件/SDK管理系统，绘制UI
