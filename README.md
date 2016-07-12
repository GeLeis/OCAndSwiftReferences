# IosAndSwiftReferences
some reference sources between study
* [Aspects](https://github.com/steipete/Aspects): oc中面相切面编程，用于运行时插入／调换方法
* [CryptoSwift](https://github.com/krzyzanowskim/CryptoSwift):swift中用语数据加密的方法库，有MD5,sha1,shae224,sha256,sha384,sha512等
* [PermissionScope](https://github.com/nickoneill/PermissionScope):swift中请求用户授权（通知，位置，相册等）
* [RxSwift](https://github.com/ReactiveX/RxSwift):swift中的reactiveCocoa
* [SwiftyJSON](https://github.com/SwiftyJSON/SwiftyJSON):swift中json数据解析
* swift编程的几个典型例子：[SwiftWeather](https://github.com/shorty-Man/SwiftWeather)，[JokeClient](https://github.com/YANGReal/JokeClient-Swift)
* [swfit指南](https://github.com/shorty-Man/SwiftGuide):swift学习资源整合
* [JSPatch](https://github.com/shorty-Man/JSPatch):JSPatch在oc和swift中的应用，用javascript书写ios应用，动态加载模块，用脚本封装原生
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
* [ios直播SDK](https://github.com/shorty-Man/LiveVideoCoreSDK)[RTMP协议介绍及相关服务器](https://blog.linuxeye.com/383.html)
* [gif图片处理](https://github.com/Flipboard/FLAnimatedImage)
* [workspace的建立使用](http://www.jianshu.com/p/b6c59d8ed2c9)
* [静态库,动态库,.a及.framework的区别](http://www.jianshu.com/p/90ef231441fc)
* [音频视频录制播放](http://www.cnblogs.com/kenshincui/p/4186022.html#avFoundationCamera)，并参考[SlowMotionVideoRecorder](https://github.com/shorty-Man/SlowMotionVideoRecorder)以及[录制后视频压缩](http://www.jianshu.com/p/7c57c58c253d)
* [swift中集成sirikit](http://www.cocoachina.com/swift/20160705/16940.html)
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
