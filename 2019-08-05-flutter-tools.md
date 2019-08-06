---
layout: post
title:  全网最全Flutter常用工具类
tag: [工具]
date: 2019-08-05
---


# 全网最全Flutter常用工具类

## Flutter工具类库
[flustars](https://link.juejin.im/?target=https://github.com/Sky24n/flustars)

1、SpUtil   : 单例"同步"SharedPreferences工具类。<br>  2、ScreenUtil   : 屏幕工具类.<br> 
3、WidgetUtil   : Widget具类.<br>  4、DirectoryUtil      : 文件目录工具类。<br>  5、DioUtil  
: 单例Dio网络工具类。

Dart常用工具类库[common_utils](https://link.juejin.im/?target=https://github.com/Sky24n/common_utils)

1、TimelineUtil : 时间轴.<br>  2、TimerUtil    : 倒计时，定时任务.<br>  3、MoneyUtil    :
精确转换，元转分，分转元，支持格式输出.<br>  4、LogUtil      : 简单封装打印日志.<br>  5、DateUtil     :
日期转换格式化输出.<br>  6、RegexUtil    : 正则验证手机号，身份证，邮箱等等.<br>  7、NumUtil      : 保留x位小数,
精确加、减、乘、除, 防止精度丢失.<br>  8、ObjectUtil   : 判断对象是否为空(String List
Map),判断两个List是否相等.<br>  9、EnDecodeUtil : md5加密，Base64加/解密.<br>  10、TextUtil    
: 银行卡号每隔4位加空格，每隔3三位加逗号，隐藏手机号等等.

### SpUtil

单例"同步"SharedPreferences工具类。支持get传入默认值，支持存储对象，支持存储对象数组。由于SharedPreferences需要异步生成才能使用。<br>

方式一：简单粗暴，等待Sp生成后再运行app。[示例项目一](https://link.juejin.im/?target=https://github.com/Sky24n/GreenTravel)<br>

方式二：增加splash页面，在splash页面完初始化，进入主页就可以同步使用。[示例项目二](https://link.juejin.im/?target=https://github.com/Sky24n/flutter_wanandroid)


### ScreenUtil

屏幕适配，兼容横/纵屏切换适配，获取屏幕宽、高、密度，AppBar高，状态栏高度，屏幕方向.


### WidgetUtil

监听Widget渲染状态，获取Widget宽高，在屏幕上的坐标，获取网络/本地图片尺寸.


### DirectoryUtil

文件目录工具类.


### DioUtil

单例DioUtil，已迁移至此处[DioUtil](https://link.juejin.im/?target=https://github.com/Sky24n/FlutterRepos/blob/master/base_library/lib/src/data/net/dio_util.dart)。(基于v1.0.13，仅供参考～)


### TextUtil


### EnDecodeUtil


### TimelineUtil

时间轴。例如：微信朋友圈，微博时间轴，支付宝时间轴。


### TimerUtil

倒计时，定时任务。


### MoneyUtil

金额工具类，分/元互转，精确转换,防止精度丢失。


### LogUtil

简单封装打印日志，可完整输出超长log。


### DateUtil

日期工具类，支付自定义格式输出。


### RegexUtil

正则工具类。


### NumUtil

数值运算工具类，保留x位小数, 精确加、减、乘、除, 防止精度丢失.


### ObjectUtil

判断对象是否为空(String List Map),判断两个List是否相等.

  

  
 
* [Flutter工具类库
flustars](https://juejin.im/post/5d0f4c54f265da1bb31c426c?utm_source=gold_browser_extension#heading-0)

* [SpUtil](https://juejin.im/post/5d0f4c54f265da1bb31c426c?utm_source=gold_browser_extension#heading-1)
* [ScreenUtil](https://juejin.im/post/5d0f4c54f265da1bb31c426c?utm_source=gold_browser_extension#heading-2)
* [WidgetUtil](https://juejin.im/post/5d0f4c54f265da1bb31c426c?utm_source=gold_browser_extension#heading-3)
* [DirectoryUtil](https://juejin.im/post/5d0f4c54f265da1bb31c426c?utm_source=gold_browser_extension#heading-4)
* [DioUtil](https://juejin.im/post/5d0f4c54f265da1bb31c426c?utm_source=gold_browser_extension#heading-5)
* [TextUtil](https://juejin.im/post/5d0f4c54f265da1bb31c426c?utm_source=gold_browser_extension#heading-6)
* [EnDecodeUtil](https://juejin.im/post/5d0f4c54f265da1bb31c426c?utm_source=gold_browser_extension#heading-7)
* [TimelineUtil](https://juejin.im/post/5d0f4c54f265da1bb31c426c?utm_source=gold_browser_extension#heading-8)
* [TimerUtil](https://juejin.im/post/5d0f4c54f265da1bb31c426c?utm_source=gold_browser_extension#heading-9)
* [MoneyUtil](https://juejin.im/post/5d0f4c54f265da1bb31c426c?utm_source=gold_browser_extension#heading-10)
* [LogUtil](https://juejin.im/post/5d0f4c54f265da1bb31c426c?utm_source=gold_browser_extension#heading-11)
* [DateUtil](https://juejin.im/post/5d0f4c54f265da1bb31c426c?utm_source=gold_browser_extension#heading-12)
* [RegexUtil](https://juejin.im/post/5d0f4c54f265da1bb31c426c?utm_source=gold_browser_extension#heading-13)
* [NumUtil](https://juejin.im/post/5d0f4c54f265da1bb31c426c?utm_source=gold_browser_extension#heading-14)
* [ObjectUtil](https://juejin.im/post/5d0f4c54f265da1bb31c426c?utm_source=gold_browser_extension#heading-15) 
