#最近更新

###Android SDK v1.1.0

####更新时间
+ 2017-5-25

####Change Log
+ 支持不存在新浪客户端情况下的网页分享。
+ 支持分享内容至新浪微博私信。

####升级提升
+ 建议升级

####升级指南
+ 首先解压您获取到的 zip 压缩包。
+ 更新库文件。
	- 打开 libs 文件夹。删除原有极光 jar 文件, 并将 jcore-android-v1.x.y.jar 、 jshare-android-v1.1.0.jar、jshare-qq-android-v1.1.0.jar、jshare-sina-android-v1.1.0.jar 以及 jshare-wechat-android-v1.1.0.jar 复制入 libs 文件夹。
用对应 CPU 文件夹下的 libjcorexxx.so 文件，替换项目中原有的极光 so 文件。
+ 更新 AndroidManifest.xml。
	- 压缩包根目录下有示例 AndroidManifest 文件。请对照示例更新跟 JShare 相关的组件属性，permission，Action 等配置。并在中文提示的位置替换你的包名 和 appkey。
+ 更新 JGShareSDK.xml。
	- 压缩包根目录下有示例 JGShareSDK 文件。请对照示例更新各个平台配置。
+ 如果使用 jcenter 的方式集成 JShare，不需要添加相关组件和资源，详细说明请参考官方集成指南。

###iOS SDK v1.1.0

####更新时间
+ 2017-5-25


####Change Log
+ 支持不存在新浪客户端情况下的网页分享。
+ 支持分享内容至新浪微博私信。
+ 修复部分 Log 错误。
+ 支持 CocoaPods。

