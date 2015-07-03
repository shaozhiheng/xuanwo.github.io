title: Together网站项目设计
date: 2015-6-30 11:08:47
tags: [实习, 项目, Together]
categories: Learn
toc: true
---
**本项目仍然处在设计阶段，一切变动以最终成果为准**

# 团队介绍
## 团队分工
- 丁皓（组长），负责网站后端建设及维护（兼产品经理？）
- 满全勇，负责网站着陆页设计&文案
- 何壁伟，负责网站内容页设计
- 马可，担任网站首席体验师

## 协同工具
- 分工：[Teambition](https://www.teambition.com/)
- 交流：[QQ](http://www.qq.com/)，[简聊](https://jianliao.com/)
- 分享：[印象笔记](https://www.yinxiang.com/)

<!-- more -->

# 公司简介
Next公司成立于2015年3月，致力于用业界最先进的技术为人们带来更好地互联网生活体验。
目前员工有产品经理兼后端工程师一名，前端工程师两名，用户体验师一名。
目前推出的产品有NextNote，已经获得三位种子用户，今天我们将带来我公司第二个产品——Together。
Next，我们在路上。

# 市场分析

## 定义
在线教育：
即e-learning，通过应用信息科技和互联网技术进行内容传播和快速学习的方法。

## 特点
- 突破时空限制、知识获取方式灵活；
- 碎片化学习、随着移动互联网的发展，移动设备更具便携性；
- 内容多样化，除了K12教育、高等教育外，还包括各类学前教育、职业教育、兴趣教育等细分领域

## 前景
- 据GSV全球教育行业报告预测，2017年全球在线教育市场规模预计将增至2555亿美元，保持23%的年复合增长率。
- 据天拓咨询估计，2017年中国在线教育市场规模将达到3000亿元人民币左右，保持31.7%的年复合增长率。
![2014年中国在线教育4](http://xuanwo.qiniudn.com/learn/2014年中国在线教育4.jpg)

*数据与图片均引用自[南方周末-2014年中国在线教育发展前景有多大？](http://www.infzm.com/content/101577)*

# 产品简介
## 特点
- 运用最新技术，革命性的改进在线教育交互体验
- 广泛运用开源技术，与开源社区保持密切合作
- 服务器要求低，可轻松承载超高并发场景

# 功能介绍
## 视频直播
运用HTML 5标准中的Canvas以及Jsmpeg技术，我们实现了我们公司高效的支持直播的在线播放器。

*当前，此技术已经运用于233手游直播APP，证明有效可行。*

## 在线聊天室
运用Node.js以及Socket.io，我们公司搭建了响应迅速的在线交流平台，其特点是可以支持大量用户同时在线交流。

## 电子白板
同样基于Node.js以及Socket.io，我们公司搭建了自研发的电子白板平台，基于教师-学生结构的主控端与受控端模型，支持在线演示。
## 虚拟计算机
运用Node.js以及Socket.io，并结合Linux平台上的Qemu虚拟化技术，我们公司首次实现了在线教育领域中的共享操作功能。

# 商业推广
## 微信推送
建立企业服务号，定期推送优质资源
## 热点聚焦
捕捉社会热点，制作相应专辑，获取群众关注
## 学校合作
通过与学校进行合作，获取第一批种子客户

# 引用资料
## 产生文档
- [使用Screen管理会话](http://xuanwo.org/2015/07/01/screen-ssh/)
- [Teambition团队协作实践](http://xuanwo.org/2015/07/02/teambition-work/)

## 参考文档
- [Node.js文档](https://nodejs.org/documentation/)
- [Socket.io文档](http://socket.io/docs/)

## 开源信息
*引用的开源库较多，如果发现有用到代码但是没有标注的，请及时通知我加上，谢谢~*
- 视频直播使用[jsmpeg](https://github.com/phoboslab/jsmpeg)
- 即时聊天使用[chat](https://github.com/Automattic/socket.io/tree/master/examples/chat)
- 在线虚拟机使用[socket.io-computer](https://github.com/kevin-roark/socket.io-computer)
- 弹幕功能使用[CommentCoreLibrary](https://github.com/jabbany/CommentCoreLibrary/)

# 版权申明
本项目是中国地质大学（北京）人文经管学院2013级信息管理与信息系统专业的暑期实习作品，以[署名-非商业性使用-相同方式共享 4.0 国际](http://creativecommons.org/licenses/by-nc-sa/4.0/)协议发布，在此协议下，您可以自由地转载或共享。

# 小小赞助
如果您对本项目感兴趣，欢迎使用支付宝扫一扫进行小额赞助以促成项目尽快上线，谢谢~
![支付宝二维码](http://xuanwo.qiniudn.com/alipay.jpg)


# 更新日志
- 2015年06月30日 完成项目设计,更新文档结构
- 2015年07月02日 添加了项目执行中产生的文档
- 2015年07月03日 完善并充实项目内容，重新调整了结构