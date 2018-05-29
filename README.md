# flutter_wanandroid
Flutter版 [玩Android \- wanandroid\.com \- 每日推荐优质文章](http://www.wanandroid.com/) 网站的移动端练手项目，总体架构完成，还有部分细节未完成。

# Android apk下载测试
[apk 下载](../flutter_wanandroid/raw/app-release.apk),该apk为release版，iOS安装包没有，可以自己下载代码安装测试。

# 效果演示（Android手机，iOS效果类似）
<img src="../flutter_wanandroid/raw/screenrecord.gif?raw=true" width="60%" height="60%">

<img src="../flutter_wanandroid/raw/Screenshot_1.png?raw=true" width="40%" height="40%" alt='首页'>
<img src="../flutter_wanandroid/raw/Screenshot_2.png?raw=true" width="40%" height="40%" alt='体系'>
<img src="../flutter_wanandroid/raw/Screenshot_3.png?raw=true" width="40%" height="40%" alt='导航'>
<img src="../flutter_wanandroid/raw/Screenshot_4.png?raw=true" width="40%" height="40%" alt='项目'>
<img src="../flutter_wanandroid/raw/Screenshot_5.png?raw=true" width="40%" height="40%" alt='侧边栏'>
<img src="../flutter_wanandroid/raw/Screenshot_6.png?raw=true" width="40%" height="40%" alt='TabBar+TabBarView界面'>

# 不足之处
1. `TabBar+TabBarView`布局（最后一张图片的布局）点击Tab快速跳转界面会出现bug，关于此问题官方还为解决 [Use TabBarView with AutomaticKeepAliveClientMixin and with 4 or more pages will cause error · Issue \#16502 · flutter/flutter](https://github.com/flutter/flutter/issues/16502)；

2. WebView控件支持不是太好，[Inline Android and iOS WebView · Issue \#730 · flutter/flutter](https://github.com/flutter/flutter/issues/730)；

3. 项目不足之处是并未完全完成：）。