

## 提问必看
**测试一定要使用vivo手机测试，不要使用其他手机安装vivo快应用引擎去测试**

**提问标准：**
- 问题描述清楚，提供复现路径，截图，录屏或者日志（提供的越详细越能快速定位问题）
- vivo小游戏引擎版本 以及 第三方游戏引擎及版本 （如不是最新版本，先都升级到最新版本看下能否解决问题）
- 提供一个简单的demo，可以去定位问题

**官方文档入口：**

小游戏开发文档入口，有入门教程，对引擎的支持，api，各个版本引擎apk下载地址[->进入<-](https://minigame.vivo.com.cn/documents/#/)

很多问题都在最新版本已经解决了，遇到问题第一步：

**检查vivo引擎是否是最新版本，（cocos，laya，egret）等是否是最新版本，建议都升级到最新版本**

[cocos最新版本下载地址](https://www.cocos.com/creator)

[laya2最新版本下载地址](https://ldc2.layabox.com/layadownload/?type=layaairide-LayaAir%20IDE%20)

[egret最新版本下载地址](https://egret.com/downloads/engine.html)

vivo引擎版本历史[->进入<-](https://minigame.vivo.com.cn/documents/#/download/engine)

## 通用问题整理

1. [vivo小游戏如何调试以及查看日志](https://github.com/vivominigame/issues/issues/9)
2. [审核被打回，没法复现bug](https://github.com/vivominigame/issues/issues/38)
3. [vivo小游戏平台引擎和调试器--安装指南](https://github.com/vivominigame/issues/issues/17)
4. [广告相关问题](https://github.com/vivominigame/issues/issues/73)
5. [游戏黑屏问题](https://github.com/vivominigame/issues/issues/92)


## 常见问题分类

快应用安装失败

https://minigame.vivo.com.cn/documents/#/lesson/question/question-environment?id=q3%ef%bc%9avivo%e6%89%8b%e6%9c%ba%e5%bf%ab%e5%ba%94%e7%94%a8%e5%ae%89%e8%a3%85%e5%a4%b1%e8%b4%a5%ef%bc%9f

快应用真机连PC调试相关

https://minigame.vivo.com.cn/documents/#/lesson/dev/dev-chrome5

广告调用问题

https://minigame.vivo.com.cn/documents/#/lesson/open-ability/ad?id=%e5%b9%bf%e5%91%8a%e6%8e%a5%e5%85%a5%e6%b3%a8%e6%84%8f%e4%ba%8b%e9%a1%b9


**审核打回**日志查看方法 

**审核打回括号里面就是机型**

https://minigame.vivo.com.cn/documents/#/lesson/dev/dev-log?id=%e5%ae%a1%e6%a0%b8%e6%89%93%e5%9b%9e%e6%97%a5%e5%bf%97%e6%9f%a5%e7%9c%8b%e8%b7%af%e5%be%84

开发时日志查看

https://minigame.vivo.com.cn/documents/#/lesson/dev/dev-log

小游戏清理缓存问题

https://minigame.vivo.com.cn/documents/#/lesson/question/question-environment?id=q6%ef%bc%9a%e5%b0%8f%e6%b8%b8%e6%88%8f%e7%9a%84%e6%95%b0%e6%8d%ae%e6%97%a0%e6%b3%95%e6%b8%85%e9%99%a4%ef%bc%8c%e6%80%8e%e4%b9%88%e5%8a%9e%ef%bc%9f

启动时长优化

https://minigame.vivo.com.cn/documents/#/lesson/minigame-test-table

如何生成release签名

https://minigame.vivo.com.cn/documents/#/lesson/base/start?id=%e5%a6%82%e4%bd%95%e7%94%9f%e6%88%90release%e7%ad%be%e5%90%8d


laya.vvmini.js 相关,用的laya版本2.3.0。情况是这样的，我发现在vivo手机上播放声音的时候会卡一下。通关游戏，每次开启游戏的时候玩第一关会卡，后面就很正常。调试跟到sound用的是minisound。一开始以为是audioCache没有用。改了源码缓存了声音，但还是卡。我发现qq用的也是minisound,但是不会卡。请问下这个跟vivo发布的这个问题怎么解决。困扰好几天了。
