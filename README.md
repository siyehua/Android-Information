#设计模式 
模式|资料
---|---
MVC|传统Android框架
[MVP](http://www.v2ex.com/t/212456#reply6)|[Android MVP 实战——MVP 在 Android 中的简单应用](http://www.v2ex.com/t/212695#reply5)
MVVM|[Android MVVM到底是啥？看完就明白了](http://mp.weixin.qq.com/s?__biz=MzA4MjU5NTY0NA==&mid=401410759&idx=1&sn=89f0e3ddf9f21f6a5d4de4388ef2c32f&scene=4#wechat_redirect)

#网络请求
项目|链接
---|---
Volley|
OKHttp|
[Retrofit](https://github.com/square/retrofit)|[Retrofit使用教程](http://www.devwiki.net/categories/Retrofit%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B/)
[RxJava](https://github.com/ReactiveX/RxJava) |[Rx入门介绍](http://blog.csdn.net/lzyzsd?viewmode=contents)
[RxJava For RxAndroid](https://github.com/ReactiveX/RxAndroid) |[Rx For Android 入门介绍](http://gank.io/post/560e15be2dca930e00da1083#toc_26)
[RxJava For RxBingding](https://github.com/JakeWharton/RxBinding)|

#图片加载
项目|链接
---|---
Volley|
ImageLoder|
Picasso|
Glide|
[Fresco](https://github.com/facebook/fresco)|
Gson|

#偷懒
项目|说明|文档
---|---|---
[Buffer Knife](https://github.com/siyehua/butterknife)|写更少的代码|[官方文档](http://jakewharton.github.io/butterknife/)
[Dagger](http://square.github.io/dagger/)|快速依赖注入器|[官方文档翻译](http://fanxu.me/post/2013-07-18#main)
[Dagger2](https://github.com/google/dagger)|[Dagger2: Step To Step](http://www.jianshu.com/p/7505d92d7748)

#数据库
项目|链接
---|---
GreenDao|

#下拉刷新

#Log
项目|说明
---|---
[logger](https://github.com/orhanobut/logger)|简洁的Log工具
[Logger](https://github.com/tianzhijiexian/logger)|[更人性化的Log](https://github.com/tianzhijiexian/Android-Best-Practices)


#工具
项目|说明
---|---
[scalpel](https://github.com/JakeWharton/scalpel)|查看布局神器
[leakcanary](https://github.com/square/leakcanary)|找出内存泄漏
[BlockCanary](http://blog.zhaiyifan.cn/2016/01/16/BlockCanaryTransparentPerformanceMonitor/)|轻松找出Android App界面卡顿元凶
[Lambda for Android](http://www.jcodecraeer.com/a/anzhuokaifa/androidkaifa/2016/0325/4078.html)|让代码更简洁,避免创建内部类


#文章
文章|
---|---
[Android应用框架演变史](http://mp.weixin.qq.com/s?__biz=MzA4MjU5NTY0NA==&mid=401314593&idx=1&sn=21d83ed33d307944937afe00abfe1ac3&scene=4#wechat_redirect)|
[关于烂代码的那些事](http://mp.weixin.qq.com/s?__biz=MzA4MjU5NTY0NA==&mid=401314593&idx=1&sn=21d83ed33d307944937afe00abfe1ac3&scene=4#wechat_redirect)|
[Android 6.0运行时权限，看这篇就够了](http://droidyue.com/blog/2016/01/17/understanding-marshmallow-runtime-permission/)|
[APK魔鬼瘦身](http://mp.weixin.qq.com/s?__biz=MzA4MjU5NTY0NA==&mid=402168736&idx=1&sn=723e9fddacfecdfbeee3d3365f6d1a2f&scene=4#wechat_redirect)|
[如何自定义Android注解？](http://mp.weixin.qq.com/s?__biz=MzA4MjU5NTY0NA==&mid=402332603&idx=1&sn=a04a622f8feb0ce35bc2356adfb18698&scene=4#wechat_redirect)|
[Android Bitmap面面观](http://mp.weixin.qq.com/s?__biz=MzA4MjU5NTY0NA==&mid=404530070&idx=1&sn=e2580b69d6ec73dabf8160216aa6702a&scene=4#wechat_redirect)|



#网站
网站|介绍
---|---
[Square](http://square.github.io/#android)|强大的开源网站
devstore:项目一体化,从开发到结束
http://www.devstore.cn/

禅道:项目管理
http://www.zentao.net/

BugTags:项目管理,错误快速反馈
https://www.bugtags.com/


TalkingData:统计.
https://www.talkingdata.com/


appsee:移动应用的页面点击可视化分析平台
https://www.appsee.com/

TwinPrime:网络优化

统计分析
国内：Talking Data, 可惜友盟现在启动就带上阿里全家桶。
国外: Flurry, 国外统计分析系统的标杆，免费的。
Crash分析
国内: 腾讯Bugly, 号称全球唯一自带ANR收集，其实原理很简单，不知别家为何不做。
国外: Crashlytics, 已经收归Twitter Fabric开发者工具集，免费好用。
推送
国内: LeanCloud，这个没实际用过，身边朋友反馈很好。
国外: Parse, 正如覃超所说,FB也在用，30qps免费限制，一般中小应用够用。
分享
国内: ShareSDK，专业做社交分享。
国外: 各社交平台自家SDK, 注意不同国家主流社交平台不同。
评论
国内：畅言, 基本抄的Disqus, 免费，算是良心产品了。
国外：Disqus, 基本不用考虑其他家的，虽然确实有竞品。
广告变现
国内：百度 or 广点通，两个效果差不多。
国外：FB or Google，做native广告，效果最佳。
支付
国内: 支付宝, 微信
国外: payssion, 专业做海外跨境收款的，能省很多事。
短信验证
国内：没用过，Google找一家最便宜的就行。
国外：Fabric Digits, twitter出品，居然不要钱。
灰度测试
国内：AppAdhoc，移动AB测试国内最专业的一家。
国外：optimizely, 支持Android, iOS, 直接在线改UI做AB测试, 三观都要颠覆了。
云测
国内：百度云测试。
国外：test in, 其实百度的也跑，国内的Android设备都卖到国外去了。
客服
国内：微客服, 有免费额度，中小应用够用。
国外：helpshift，国外最专业的客服平台。
推广
国内：这个真不了解。
国外：Appsflyer, 海外推广为数不多的选择之一。
可视化分析
国内：growingio, 还在内测中，linkedin数据分析大牛回国创业，据说黑科技，可以直接在app上实时查看各种转化
率数据。
国外：appsee, 绝对黑科技，PM最爱，转化率什么的再也不怕上不去了，用过后我们团队成员一致好评，在我的微
信公众号里有专门文章介绍使用体验。

Dagger, jsr250

Rx大家族: RxJava, RxAndroid, RxBinding

Retrofit

EventBus

Realm

support库, data binding

LeakCanary, BlockCanary

        
