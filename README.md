# IosAndSwiftReferences，连接最后为跟贴时间，方便获取最新的资料
some reference sources between study
* [Aspects](https://github.com/steipete/Aspects): oc中面相切面编程，用于运行时插入／调换方法
* [CryptoSwift](https://github.com/krzyzanowskim/CryptoSwift):swift中用语数据加密的方法库，有MD5,sha1,shae224,sha256,sha384,sha512等
* [PermissionScope](https://github.com/nickoneill/PermissionScope):swift中请求用户授权（通知，位置，相册等）
* [RxSwift](https://github.com/ReactiveX/RxSwift):swift中的reactiveCocoa
* [SwiftyJSON](https://github.com/SwiftyJSON/SwiftyJSON):swift中json数据解析
* swift编程的几个典型例子：[SwiftWeather](https://github.com/shorty-Man/SwiftWeather)，[JokeClient](https://github.com/YANGReal/JokeClient-Swift)
* [swfit指南](https://github.com/shorty-Man/SwiftGuide):swift学习资源整合
* [JSPatch](https://github.com/shorty-Man/JSPatch):JSPatch在oc和swift中的应用，用javascript书写ios应用，动态加载模块，用脚本封装原生,[JSPatch使用](http://www.voidcn.com/blog/jueyi1127/article/p-5756877.html)
* [swift中常用的10个框架](http://www.cocoachina.com/swift/20160525/16437.html)
* [网络图片资源](http://imgur.com )
* reactNative[中文教程](http://reactnative.cn),[中文社区](http://bbs.reactnative.cn),[ES6语法](http://bbs.reactnative.cn/topic/15/react-react-native-的es5-es6写法对照表),[关于脚本封装原生存在的问题](http://bbs.reactnative.cn/topic/14/react-native-把现代web科技带给移动开发者/2),[javascript常用语法](http://reactnative.cn/docs/0.26/javascript-environment.html#content),[js.coachJS开源框架](https://js.coach/react-native/react-native-linear-gradient),[ECMAScript 6入门](http://es6.ruanyifeng.com/#README),[react native博客](http://www.cocoachina.com/ios/20160612/16654.html)
* [Swift编程思想-guard try? if 应用](http://www.cocoachina.com/swift/20160613/16632.html)
* [类似网易的顶层分页导航](https://github.com/tianzhuo112/VTMagic)
* [swift中版本比较](http://nshipster.cn/swift-system-version-checking/)
* [插播一条Android Studio使用教程](http://www.open-open.com/lib/view/open1433387390635.html)
* [session保存登录状态信息](http://www.tuicool.com/articles/7NV3ueJ)
* [3DTouch在ios中的应用](http://www.cocoachina.com/ios/20160628/16825.html)
* [IOS10中自定义Notification界面](http://www.cocoachina.com/ios/20160628/16833.html)
* [git使用手册](http://www.cocoachina.com/ios/20160629/16855.html)
* [IQKeyboard解决键盘遮挡textView的placeholder问题](https://github.com/shorty-Man/IQKeyboardManager)
* [编程风格指南](http://www.cocoachina.com/swift/20160701/16894.html)
* [ios直播SDK](https://github.com/shorty-Man/LiveVideoCoreSDK),[RTMP协议介绍及相关服务器](https://blog.linuxeye.com/383.html),[直播全教程16/7/22](http://www.cocoachina.com/ios/20160721/17133.html),     [520直播教程](https://github.com/GrayJIAXU/520Linkee) [仿映客刷礼物效果](https://github.com/cooxu/PresentAnimView)
* [gif图片处理](https://github.com/Flipboard/FLAnimatedImage)
* [workspace的建立使用](http://www.jianshu.com/p/b6c59d8ed2c9)
* [静态库,动态库,.a及.framework的区别](http://www.jianshu.com/p/90ef231441fc)
* [音频视频录制播放](http://www.cnblogs.com/kenshincui/p/4186022.html#avFoundationCamera)，并参考[SlowMotionVideoRecorder](https://github.com/shorty-Man/SlowMotionVideoRecorder)以及[录制后视频压缩](http://www.jianshu.com/p/7c57c58c253d)
* [swift中集成sirikit](http://www.cocoachina.com/swift/20160705/16940.html)[sirikit教程](http://www.cocoachina.com/swift/20160720/17123.html)
* [ios10中collectionView和tableView优化](http://www.cocoachina.com/ios/20160706/16952.html)
* [多线程安全处理](http://www.cocoachina.com/ios/20160707/16957.html)
* 关于模拟器显示appIcon而真机却无法显示，可能是因为直接将jpg图片改成了png格式，这样是无法解析的。
* [CALayer的应用](http://www.cocoachina.com/ios/20160711/17007.html)
* [设计中的微交互效果](http://www.cocoachina.com/design/20160712/17014.html)
* [tableView滚动过程中cell试图也在滚动](http://www.cocoachina.com/ios/20160712/17011.html)
* 关于状态栏的改变，可以在baseNavigationController中调用如下方法来改变不同controller中的状态栏
```objc
-(UIStatusBarStyle)preferredStatusBarStyle{
	if ([self.childViewControllers.lastObject isKindOfClass:[LYBMineRootViewController class]]) {
		return UIStatusBarStyleLightContent;
	}
	return UIStatusBarStyleDefault;
}

```
* [ios中的宏定义](http://www.cocoachina.com/ios/20160713/17026.html)
* [ios中.a和framework的创建](http://www.cocoachina.com/ios/20160713/17025.html)
* [ios开发中wifi，网络ip开发](http://www.cocoachina.com/ios/20160715/17022.html)
* [自定义loading，及加载失败时refresh](https://github.com/jinxiansen/JHUD)
* 屏蔽右滑返回功能
```objc
if ([self.navigationController respondsToSelector:@selector(interactivePopGestureRecognizer)]) {
		self.navigationController.interactivePopGestureRecognizer.enabled = NO;
	}
```
* [CSStickyHeaderFlowLayout实现collectionView顶部视图的固定，视差，缩放](https://github.com/jamztang/CSStickyHeaderFlowLayout)
* @dynamic 关键字是相对于 @synthesize 的，它们用样用于修饰 @property，用于生成对应的的 getter 和 setter 方法。但是 @ dynamic 表示这个成员变量的 getter 和 setter 方法并不是直接由编译器生成，而是手工生成或者运行时生成。
* [UIButton解决同时点击多个按钮](http://xiongzenghuidegithub.github.io/blog/2016/04/22/runtimeying-yong-fang-zhi-an-niu-lian-xu-dian-ji/)
* 导航栏背景样式设置
```objc
navigationItem.prompt = @"导航标题上方显示的提示内容",如果有值，那么导航栏高度会增加
self.navigationItem.title = @"标题";

UIBarMetricsDefault表示导航栏默认状态，包括横屏竖屏
UIBarMetricsCompact表示导航栏横屏状态
UIBarMetricsDefaultPrompt表示默认状态，并且navigationItem.prompt有值的情况下
```
* mac终端常用的命令
```
control+u删除一整条命令，从新输入
sudo !!相当于  sudo {上一条命令}，这样方便在漏掉sudo的情况下，快速执行上一条命令
!＋字母，执行上一条以特定字母开头的命令
history 查询命令历史
&&将两条命令合并成一条命令
reset将目前终端屏幕上的内容情况
```
* [ios中图表绘制](https://github.com/danielgindi/Charts)
* _cmd表示当前方法的selector，
* 文本阴影NSShadow
```objc
NSShadow *shadow = [NSShadow new];
shadow.shadowOffset = CGSizeZero;
shadow.shadowBlurRadius = 5.0f;
shadow.shadowColor = [UIColor colorWithWhite:0.0f alpha:0.3f];
NSAttributedString *attString = [[NSAttributedString alloc] initWithString:@"www.olinone.com" attributes:@{NSShadowAttributeName: shadow, NSForegroundColorAttributeName: [UIColor whiteColor]}];
lbl.attributedText = attString;
实际效果是这样的，shadowBlurRadius值越小，文本描边越清晰
```
* 数字签名:理解了非对称加密和摘要算法，来看一下数字签名。实际上数字签名就是两者结合。假设，我们有一段授权文本，需要发布，为了防止中途篡改文本内容，保证文本的完整性，以及文本是由指定的权限狗发的。首先，先将文本内容通过摘要算法，得到摘要，再用权限狗的私钥对摘要进行加密得到密文，将源文本、密文、和私钥对应的公钥一并发布即可。那么如何验证呢？
验证方首先查看公钥是否是权限狗的，然后用公钥对密文进行解密得到摘要，将文本用同样的摘要算法得到摘要，两个摘要进行比对，如果相等那么一切正常。这个过程只要有一步出问题就视为无效。


* [ipa的组成](http://www.pchou.info/ios/2015/12/14/ios-certification-and-code-sign.html)
* [ios动画,UIview](http://www.cocoachina.com/ios/20160727/17199.html)
* [POP动画框架教程16/7/28](http://www.ui.cn/detail/21148.html)
* [动画的时间控制CAMediaTimingFunction贝赛尔曲线](http://cubic-bezier.com/)
