# OCAndSwiftReferences
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
* [git使用手册](http://www.cocoachina.com/ios/20160629/16855.html)  [version manager](http://blog.csdn.net/ithomer/article/details/7529022)
* [IQKeyboard解决键盘遮挡textView的placeholder问题](https://github.com/shorty-Man/IQKeyboardManager)
* [编程风格指南](http://www.cocoachina.com/swift/20160701/16894.html)
* [ios直播SDK](https://github.com/shorty-Man/LiveVideoCoreSDK),[RTMP协议介绍及相关服务器](https://blog.linuxeye.com/383.html),[直播全教程16/7/22](http://www.cocoachina.com/ios/20160721/17133.html),  [高仿斗鱼界面](http://code.cocoachina.com/download/128246)   [520直播教程](https://github.com/GrayJIAXU/520Linkee) [仿映客刷礼物效果](https://github.com/cooxu/PresentAnimView)
* [gif图片处理](https://github.com/Flipboard/FLAnimatedImage)
* [基于AFNetworking的封装网络库YTKNetwork](https://github.com/yuantiku/YTKNetwork)
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
* [类似美团的下拉菜单](https://github.com/jsfu/JSDropDownMenu)
* 屏蔽右滑返回功能
```objc
if ([self.navigationController respondsToSelector:@selector(interactivePopGestureRecognizer)]) {
		self.navigationController.interactivePopGestureRecognizer.enabled = NO;
	}
```
* [CSStickyHeaderFlowLayout实现collectionView顶部视图的固定，视差，缩放](https://github.com/jamztang/CSStickyHeaderFlowLayout)
* @dynamic 关键字是相对于 @synthesize 的，它们用样用于修饰 @property，用于生成对应的的 getter 和 setter 方法。但是 @ dynamic 表示这个成员变量的 getter 和 setter 方法并不是直接由编译器生成，而是手工生成或者运行时生成。
* [UIButton解决同时点击多个按钮,按钮点击事件拦截](http://xiongzenghuidegithub.github.io/blog/2016/04/22/runtimeying-yong-fang-zhi-an-niu-lian-xu-dian-ji/)
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
* [POP动画框架教程](http://www.ui.cn/detail/21148.html)
* [动画的时间控制CAMediaTimingFunction贝赛尔曲线](http://cubic-bezier.com/),  [贝赛尔曲线的控制点的意义，参照三次贝赛尔曲线动图](http://www.cocoachina.com/ios/20160919/17592.html)
* [ReactiveCocoa常用方法及类](http://www.cocoachina.com/ios/20160729/17236.html)
* 自己做data缓存,比如图片,可以用sdCycleScrollView的Nsdate+sdDataCache
* 利用caLyaer在指定时间内画图
```objc
	UIBezierPath *path = [UIBezierPath bezierPath];
	[path moveToPoint:CGPointMake(200, 100)];
	[path addLineToPoint:CGPointMake(170, 170)];
	[path addLineToPoint:CGPointMake(230, 170)];
	[path closePath];
	
	CAShapeLayer *layer = [CAShapeLayer layer];
	layer.path = path.CGPath;
	layer.lineCap = kCALineCapRound;
	layer.lineJoin = kCALineJoinRound;
	layer.strokeColor = [UIColor redColor].CGColor;
	layer.fillColor = nil;
	CABasicAnimation * HideAnim = [CABasicAnimation animationWithKeyPath:@"strokeEnd"];
	[HideAnim setFromValue:@0.0];//0~1是，从无到有
	[HideAnim setToValue:@1.0];
	[HideAnim setDuration:3];
	HideAnim.beginTime = CACurrentMediaTime() + 2;//表示2s后执行该动画
	HideAnim.removedOnCompletion = NO;
	HideAnim.fillMode = kCAFillModeForwards;
	HideAnim.timingFunction = [CAMediaTimingFunction functionWithName:kCAMediaTimingFunctionLinear];
	[layer addAnimation:HideAnim forKey:@"hid"];
	[self.view.layer addSublayer:layer];
```
* [YYCache快速建立sqlite缓存](https://github.com/shorty-Man/YYCache)
* [IOS10推送通知开发](http://www.cocoachina.com/ios/20160804/17278.html) ,,[UserNotifications](http://www.cocoachina.com/ios/20160926/17645.html)
* [设计准则](http://www.cocoachina.com/design/20160804/17292.html)
* [ios开发工具下载](https://developer.apple.com/download/   )
* [UISearchController的使用](https://github.com/shorty-Man/searchControllerDemo)
* 制作任意形状的UIImageView
```objc
	_imageView = [[UIImageView alloc] initWithFrame:CGRectMake(20, 220, 75, 85)];
	CALayer *maskLayer = [CALayer layer];
	maskLayer.frame = self.imageView.bounds;
	//设定边界样式的图片,实际的ImageView可大可小，按照一定比例设定边界样式图片的大小就好
	UIImage *maskImage = [UIImage imageNamed:@"start_leader_decision_big"];
	maskLayer.contents = CFBridgingRelease(maskImage.CGImage);
	self.imageView.layer.mask = maskLayer;
	[self.view addSubview:_imageView];
	//给视图赋值图片
	self.imageView.image = [UIImage imageNamed:@"role_level0_f"];
```
* [隐藏navigatorBar下方的黑线](http://www.cocoachina.com/special/20160914/17582.html)
```objc
	[self.navigationController.navigationBar setBackgroundImage:[UIImage new] forBarMetrics:UIBarMetricsDefault];
	[self.navigationController.navigationBar setShadowImage:[UIImage new]];
```
* 解决scrollView中点击cell不能push出下个页面，但是可以通过popGesture返回。在当前controller中
```objc
-(void)viewDidload{
if ([self.navigationController respondsToSelector:@selector(interactivePopGestureRecognizer)]) {
        self.navigationController.interactivePopGestureRecognizer.delegate = self;
}
}

#pragma mark - UIGestureRecognizerDelegate代理方法
- (BOOL)gestureRecognizerShouldBegin:(UIGestureRecognizer *)gestureRecognizer{
    return NO;
}

```
* [地图定位](http://code.cocoachina.com/download/132371) [当前定位](http://www.cocoachina.com/ios/20160919/17596.html)
```objc
	CLPlacemark *place = placemarks[0];
        self.title = place.name;
        NSLog(@"name,%@",place.name);                       // 位置名
        NSLog(@"thoroughfare,%@",place.thoroughfare);       // 街道
        NSLog(@"subThoroughfare,%@",place.subThoroughfare); // 子街道
        NSLog(@"locality,%@",place.locality);               // 市
        NSLog(@"subLocality,%@",place.subLocality);         // 区
	NSLog(@"%@",place.administrativeArea);              //省
	NSLog(@"%@",place.subAdministrativeArea);
	NSLog(@"inlandWater%@",place.inlandWater);
        NSLog(@"country,%@",place.country);                 // 国家
        NSLog(@"error %@",error);
       
```
* 通过viewWithTag方法来获取subView时，如果某个subView显示在父view之外，那么通过该方法是获取不到这个subview的
* [通过两个相对的view，设置上层view的mask来形成视觉差效果](http://www.cocoachina.com/ios/20160811/17340.html)
* [ios中的runtiem,runloop理解](http://www.cocoachina.com/ios/20160817/17373.html)
* [ios中图片拉伸而不改变轮廓](https://github.com/shorty-Man/popmenuIos)
```objc
image = [[UIImage imageNamed:@"pop_black_backGround"] resizableImageWithCapInsets:UIEdgeInsetsMake(15, 5, 15, 5)];
//其中Insets这个参数的格式是(top,left,bottom,right)，从上、左、下、右分别在图片上画了一道线，这样就给一个图片加了一个框。只有在框里面的部分才会被拉伸，而框外面的部分则不会改变。
```
* 自定义按钮时如果指定style为system，那么设置背景图片时，会导致渲染颜色改变。应指定为custom
* 手势共存
```objc
	//指定两个手势共存,,前者等待后者，确定后者不响应的情况下，前者才会响应
	stylesCollectionView.panGestureRecognizer.requireGestureRecognizerToFail(navigationController!.panGestureRecognizer)
```
* 自动以导航控制器的跳转实现UIViewControllerAnimatedTransitioning协议
* [使用Cocoapods管理第三方库出现Undefined symbols for architecture i386 解决方法](http://www.jianshu.com/p/6c9de468337a)
* 根据图片纹路进行渲染，改变图片颜色
```objc
	func imageWithColor(color:UIColor) -> UIImage {
		UIGraphicsBeginImageContextWithOptions(self.size, false, self.scale)
		let context = UIGraphicsGetCurrentContext()
		CGContextTranslateCTM(context, 0, self.size.height)
		CGContextScaleCTM(context, 1.0, -1.0)
		CGContextSetBlendMode(context, CGBlendMode.Normal)
		let rect = CGRectMake(0, 0, self.size.width, self.size.height)
		CGContextClipToMask(context, rect, self.CGImage)
		color.setFill()
		CGContextFillRect(context, rect)
		let newImage = UIGraphicsGetImageFromCurrentImageContext()
		UIGraphicsEndImageContext()
		return newImage
		
	}
```
* [CAGradientLayer的使用](https://zsisme.gitbooks.io/ios-/content/chapter6/cagradientLayer.html)
```objc
-(CAGradientLayer *)backgroundLayer{
    CAGradientLayer *gradientLayer = [CAGradientLayer layer];
    gradientLayer.frame = self.view.bounds;
    gradientLayer.colors = @[(__bridge id)[UIColor purpleColor].CGColor,(__bridge id)[UIColor redColor].CGColor];
    gradientLayer.startPoint = CGPointMake(0.5, 0);//左上角是0,0,
    gradientLayer.endPoint = CGPointMake(0.5, 1);
    gradientLayer.locations = @[@0.65,@1];//第一个是渐变开始的位置，最后一个是渐变结束的位置
    return gradientLayer;
}
```
* [ios核心动画高级技巧](https://zsisme.gitbooks.io/ios-/content/chapter1/the-layer-tree.html)
* [炫丽的自定义登录界面]（https://github.com/shorty-Man/customeLogin）
* 任何uiview都可以通过layer的contents属性，设置一张图片为背景
* layer有个contentsGravity属性，如果iamgeView的ContentMode一样，调整layer的内容展现方式
* layer.contentsScale用于设置每个点绘制的像素的个数，默认为1,(应用：layer.contentsScale = image.scale)
* 调用layer的display方法，会触发-(void)displayLayer:(CALayer *)layer，如果没有实现这个方法，那么就会触发-(void)drawLayer:(CALayer *)layer inContext:(CGContextRef)ctx，这两个都是CALayerDelegate方法，非正式协议
* frame的w和h并不一定与bounds的w和h一致，frame代表的是图层外部(水平垂直交叉后形成的轴)坐标，bounds是指内部坐标，contentView视图相对于自身的坐标，当view发生旋转时，frame，bounds就可能不一样了
* 通过设置layer的zposition来设置layer的前后关系，越大，那么就越不会被遮住
* layer的containsPoint:接受一个在本图层坐标系下的CGPoint，如果这个点在图层frame范围内就返回YES
* 可以通过layer的hitTest方法来判断point是否在layer对应的范围内，point可以通过touchBegan或者UIGestureRecognize的locationInView方法获得
* 同一个view同时设置masktoBounds进行裁剪和阴影效果时，阴影被裁剪到，看不到，只有用同样大小的view包裹需要进行裁剪的view,用外层的view设置阴影即可。
* 设置shouldRasterize（栅格化）为yes，可以消除layer存在子图层是，透明度不统一的情况，设置为yes后，图层及子图层都会被当作一个整体
```objc
	button2.layer.shouldRasterize = YES;
	button2.layer.rasterizationScale = [UIScreen mainScreen].scale;//防止出现像素化的问题

```
* calayer对应view的transform的属性为affineTransform
* CGAffineTransformRotate(CGAffineTransform t, CGFloat angle)可以用来做混合变换，即可以在之前变换的基础上做其他的变换，CGAffineTransformMakeRotation(M_PI_4)适用于单独变幻
* #define DEGREES_TO_RADIANS(x) ((x)/180.0*M_PI)   角度转弧度
* #define RADIANS_TO_DEGREES(x) ((x)/M_PI*180.0)   弧度转角度
* 通过设置transform.m34 = - 1.0 / 500.0;来设置3d情形下的透视效果。
* calayer有一个doublesided属性，当view的正面消失时，yes绘制反面内容，no不绘制
* calayer的每个子图层都是独立的，分别在不同的3d空间
* [layer中光亮和阴影,3维立方体](https://zsisme.gitbooks.io/ios-/content/chapter5/solid-objects.html)
* 单独指定圆角
```objc
CGRect rect = CGRectMake(50, 50, 100, 100);
CGSize radii = CGSizeMake(20, 20);
UIRectCorner corners = UIRectCornerTopRight | UIRectCornerBottomRight | UIRectCornerBottomLeft;
//create path
UIBezierPath *path = [UIBezierPath bezierPathWithRoundedRect:rect byRoundingCorners:corners cornerRadii:radii];
```
* [Method Swizzling的各种姿势](http://www.cocoachina.com/ios/20160826/17422.html)
* [CAEmitterLayer发射器的使用]
```objc
	CAEmitterLayer *emitter =  [CAEmitterLayer layer];
	emitter.frame = self.containView.bounds;
	[self.containView.layer addSublayer:emitter];
	
	
	emitter.renderMode = kCAEmitterLayerAdditive;//将重叠的部分的亮度看上去更亮
	emitter.emitterPosition = CGPointMake(emitter.frame.size.width / 2, emitter.frame.size.height/ 2);
	
	CAEmitterCell *cell = [[CAEmitterCell alloc] init];
	cell.contents = (__bridge id _Nullable)([UIImage imageNamed:@"evaluation_small-red"].CGImage);
	cell.birthRate = 150;
	cell.lifetime = 5.0;
	cell.color = [UIColor colorWithRed:1 green:0.5 blue:0.1 alpha:1].CGColor;
	cell.alphaSpeed = -0.1;//意思是说粒子透明度每过一秒就减0.1
	cell.velocity = 100;//粒子移动的数度
	cell.velocityRange = 50;//粒子活动的范围
	cell.emissionRange = 0.001;//360度发射  2 * M_PI
	emitter.preservesDepth = NO;//是否将3D粒子系统平面化到一个图层
	
	emitter.emitterCells = @[cell];
```
* [图层动画行为](https://zsisme.gitbooks.io/ios-/content/chapter7/layer-actions.html)  [CAAnimation](http://www.jianshu.com/p/81b571e931cf)
* 图层在移动的过程中，通过呈现视图的hitTest方法来响应用户事件--呈现与规模
```objc
- (void)touchesBegan:(NSSet *)touches withEvent:(UIEvent *)event
{
	//get the touch point
	CGPoint point = [[touches anyObject] locationInView:self.view];
	//check if we've tapped the moving layer
	if ([self.colorLayer.presentationLayer hitTest:point]) {
		//randomize the layer background color
		CGFloat red = arc4random() / (CGFloat)INT_MAX;
		CGFloat green = arc4random() / (CGFloat)INT_MAX;
		CGFloat blue = arc4random() / (CGFloat)INT_MAX;
		self.colorLayer.backgroundColor = [UIColor colorWithRed:red green:green blue:blue alpha:1.0].CGColor;
	} else {
		//otherwise (slowly) move the layer to new position
		[CATransaction begin];
		[CATransaction setAnimationDuration:4.0];
		self.colorLayer.position = point;
		[CATransaction commit];
	}
}
```
* [贝赛尔曲线的控制点,起止点，与曲线形状的关系](http://luoxianming.cn/2016/07/02/UIBezierPath/)
* CAKeyframeAnimation动画过程中自动改变layer的方向与曲线切线一致
```objc
	animation.rotationMode = kCAAnimationRotateAuto;  
```
* CAKeyframeAnimation用于连续的动画变化，CABasicAnimation用于一次性的值变化
* CATransition  过渡动画，图层行为,一个图层只能添加一个CATransition
* 图层截图
```objc
	UIGraphicsBeginImageContext(layer.bounds.size);
	[layer renderInContext:UIGraphicsGetCurrentContext()];
	UIImage *image=UIGraphicsGetImageFromCurrentImageContext();
	UIGraphicsEndImageContext();
```
* animation.autoreverses = YES设置动画执行完毕后自动逆向执行
* INFINITY无穷大
* animation.beginTime = 1，默认为0，是指动画从添加到可见图层到开始执行的时间间隔
* animation.timeOffset = 0.5,这是指动画开始快进0.5s开始，比如说执行duration为1s，那么从一半的时候开始
* animation.speed = 2,动画执行的速度，默认为1，如果为2,那么动画执行的速度快一倍，duration为2的动画会被压缩到1s，如果原来的timeOffset为1，那么则从动画执行结束的地方开始。
* CFTimeInterval time = CACurrentMediaTime();马赫时间
* 修改layer的speed属性可以暂停(0)，倒退，快进动画，默认为1
* animation.timingFunction = [CAMediaTimingFunction functionWithName:kCAMediaTimingFunctionEaseIn];设置动画执行的速度
* CADisplayLink有个frameInterval属性，表示多少帧执行一次，默认为1，CADisplayLink可以同时加入多个runloop模式，于是可以同时加入NSDefaultRunLoopMode和UITrackingRunLoopMode来保证它不会被滑动打断，也不会被其他UIKit控件动画影响性能，
```objc
self.timer = [CADisplayLink displayLinkWithTarget:self selector:@selector(step:)];
[self.timer addToRunLoop:[NSRunLoop mainRunLoop] forMode:NSDefaultRunLoopMode];
[self.timer addToRunLoop:[NSRunLoop mainRunLoop] forMode:UITrackingRunLoopMode];
```
* scheduledTimerWithTimeInterval创建NSTimer会自动加入runLoop，通过timerWithTimeInterval创建的NSTimer需要手动加入runloop
* IOS9之后uiimageView圆角不会触发离屏渲染，uibutton会触发
* [离屏渲染](https://github.com/seedante/OptimizationForOffscreenRender)如果需要设置遮罩，离屏渲染解决方法1⃣️利用core graphic自己按照遮罩绘图,获取想要形状的图,片,此方法不兼容sdWebImage，
```objc
func drawImage(image originImage: UIImage, rectSize: CGSize, roundedRadius radius: CGFloat) -> UIImage {
    let rect = CGRect(origin: CGPoint(x: 0, y: 0), size: rectSize)
    UIGraphicsBeginImageContextWithOptions(rect.size, false, UIScreen.mainScreen().scale)
    let currentContext = UIGraphicsGetCurrentContext()
    
    CGContextAddPath(currentContext,
                     UIBezierPath(roundedRect: rect,
                        byRoundingCorners: .AllCorners,
                        cornerRadii: CGSize(width: radius, height: radius)).CGPath)
    CGContextClip(currentContext)
    
    //Don't use CGContextDrawImage, coordinate system origin in UIKit and Core Graphics are vertical oppsite.
    originImage.drawInRect(rect)
    CGContextDrawPath(currentContext, .FillStroke)
    let roundedCornerImage = UIGraphicsGetImageFromCurrentImageContext()
    UIGraphicsEndImageContext()
    
    return roundedCornerImage
}
```
2⃣️制作一个遮罩view，大小与底层的uiiamgView一致，并设置上层遮罩view的遮罩图片.

* 可以通过let bgView = navigationBar.valueForKey("_backgroundView") as? UIView 获取导航栏的背景view
* [swift小demo，涉及almofire,swfitJson](http://code.cocoachina.com/view/132752)
* [风格不一样的MRProgress](https://github.com/mrackwitz/MRProgress)
* [解决同时发生两个请求，loadingView和noInternetView的弹出消失问题](http://www.jianshu.com/p/07eb268c93f2)
* [iOS中UIDynamic物理仿真详解](http://www.jianshu.com/p/e096d2dda478)
* [HCSStarRatingView星星评分控件](http://code.cocoachina.com/download/126259)
* [NumberMorphView创新的数字变动swift](https://github.com/me-abhinav/NumberMorphView)
* [BTNavigationDropdownMenu下拉菜单Swift](https://github.com/PhamBaTho/BTNavigationDropdownMenu)
* [app安全](http://mp.weixin.qq.com/s?__biz=MjM5OTM0MzIwMQ==&mid=2652547386&idx=5&sn=b70d911ddba8debd2aa086a24bf79407&scene=1&srcid=0902VcWhzkGEFcqUx98OqZGh#rd)[接口加密](https://segmentfault.com/q/1010000002714271)
* frame是相对于父视图，bounds是相对于自身坐标系统来说，如果改变bounds.origin，会改变其自视图的位置，scrollView的原理即如此
* [两个tableView之间的联动,tableView与collectionView之间的联动](https://github.com/leejayID/Linkage)
* [多任务下载，断点下载](http://code.cocoachina.com/download/129554)
* [RSA加密](https://github.com/ideawu/Objective-C-RSA)[ ,AES加密](http://code.cocoachina.com/download/128370)
* [swift开发的图表库，折线｜柱状｜饼状](http://code.cocoachina.com/download/125586) ,[OC版](https://github.com/China131/JHChart)
* [正则表达式](http://www.jb51.net/article/73342.htm) \d用于匹配任意数字，\w匹配字母数字下划线
* [日志纪录工具](https://github.com/CocoaLumberjack/CocoaLumberjack)，以及取沙盒日志的方法
```objc
	1.手机连接Mac电脑，打开Xcode。
	2.选择顶栏的 Windows 下的 Devices。
	3.在Devices栏下先选择当前连接的手机设备。
	4.在 Installed Apps 栏下选择你开发的App（需要取沙盒文件的App）。
	5.点击底部“齿轮图案”的按钮，选择Download Container…
```
* [导航控制器子控制器之间的任意跳转](http://www.cocoachina.com/ios/20160905/17457.html)
* [launchImage引发的问题](http://www.cocoachina.com/bbs/read.php?tid-1693460.html)
* [自定义刷新控件](https://github.com/DaMingShen/SURefresh)
* [GCD同步锁在属性设置上的应用](http://www.cocoachina.com/special/20160907/17512.html)
* [关于如何将自己的库添加cocoapods支持](http://www.cocoachina.com/ios/20160907/17501.html)
* [下载按钮动画](https://github.com/Josin22/JSDownloadView)
* [gif制作软件](http://www.cockos.com/licecap)
* [static Cell和dynamic cell的混合使用](http://www.cocoachina.com/ios/20160909/17518.html)
* [图片元数据的读写](http://www.cocoachina.com/ios/20160909/17519.html)
* [Mac上常用软件](http://www.cocoachina.com/ios/20160909/17521.html)
* [圆形采色器,28l](http://www.cocoachina.com/bbs/read.php?tid-1693814-page-3.html)
* [修改系统控件的显示样式](http://www.cocoachina.com/ios/20160914/17579.html)
* [文件下载器](http://www.jianshu.com/p/6be80f0067ee)
* [UIStackView](http://www.jianshu.com/p/213702004d0d)
* [多线程并发流程控制dispatch_group_notify](http://blog.csdn.net/wangzitao126/article/details/43195533)
* [关于使用SDWebImage下载图片造成内存暴增crash的解决方法](http://www.cocoachina.com/ios/20160920/17602.html)
* 截屏与在指定范围内截屏
```objc
UIView *snapshot = [fromView snapshotViewAfterScreenUpdates:NO];

UIView *snapshot = [fromViewSnapshot resizableSnapshotViewFromRect:snapshotRegion afterScreenUpdates:NO withCapInsets:UIEdgeInsetsZero];
```
* [Objective-c消息转发](http://www.cocoachina.com/ios/20160921/17608.html)
```objc
接下来说一下types参数，
比如我们要添加一个这样的方法：-(int)say:(NSString *)str;
相应的实现函数就应该是这样：

int say(id self, SEL _cmd, NSString *str) 
{ 
    NSLog(@"%@", str); 
    return 100;//随便返回个值 
 } 
class_addMethod这句就应该这么写：

class_addMethod([EmptyClass class], @selector(say:), (IMP)say, "i@:@");
其中types参数为"i@:@“，按顺序分别表示：

i  返回值类型int，若是v则表示void

@  参数id(self)

:  SEL(_cmd)

@  id(str),如果没有参数最后一个@可以不要
```
* [类似社交图片浏览PYPhotoBrowser](https://github.com/iphone5solo/PYPhotoBrowser)
* AFNetworking里面默认Post方式的参数是放在body里面，其他方式get ,head, delete是放在url里面的
* [IOS后台实时定位](http://www.cocoachina.com/ios/20160927/17652.html)
* [javascript，html5，reactnative知识](http://www.cocoachina.com/industry/20160928/17662.html)
* IOS9以前键盘弹出的情况下，点击键盘也会出发键盘下面view的hitTest方法
* [颜色渐变](http://www.jianshu.com/p/3e0e25fd9b85)
* [丝滑右滑返回FDFullscreenPopGesture](https://github.com/forkingdog/FDFullscreenPopGesture)
* IOS环境下openURL的用法
```objc
if ([app respondsToSelector:@selector(openURL:options:completionHandler:)]) {
					NSDictionary *options = @{UIApplicationOpenURLOptionUniversalLinksOnly : @YES};
					[app openURL:settingsURL options:options completionHandler:nil];
				}else{
					[app openURL:settingsURL];
				}
```

* 解决xcode中使用git管理时存在的UserInterfaceState.xcuserstate问题[1,](http://blog.csdn.net/lovenjoe/article/details/50053255),在每次分支和初始化项目时，直接删除UserInterfaceState.xcuserstate，配置文件不知道为什么不管用
* [为什么说给予tcp的移动端IM仍然需要心跳保活](http://www.cocoachina.com/ios/20161111/18042.html)
* [NSException的使用，补货异常，防止程序崩溃](http://www.cocoachina.com/ios/20161111/18046.html)
* [多种分格的搜索页面](https://github.com/iphone5solo/PYSearch)
* [字体高亮可点击](http://code.cocoachina.com/view/129659)
* [UIMenuController的应用](http://www.wtoutiao.com/p/deaRZw.html)
* [UITableview右滑触线的菜单](http://www.cocoachina.com/ios/20161114/18070.html)
* [39个优秀的swiftUI开源库](http://www.cocoachina.com/ios/20161109/18007.html)
* [oc优秀的开源项目](https://github.com/thedillonb/CodeHub)
* [Widget的简单应用并适配iOS10](http://www.cocoachina.com/ios/20161115/18078.html)
* [svgKit的使用](https://github.com/SVGKit/SVGKit)
* openURL方法的options参数，通过key(sourceApplication)来确定原来的app
* [FRDIntent用于解决应用间跳转和应用内部页面跳转](https://github.com/douban/FRDIntent)
* [charles资源](http://xclient.info/s/charles.html)
* [masonry使用技巧](http://www.jianshu.com/p/99c418cd11f7)
* [用NSTemporaryDirectory()临时保存文件](http://stackoverflow.com/questions/40625265/avaudiorecorder-can-we-record-without-saving-into-file)
* [如何解决10分钟内没有触摸屏幕就跳到登录界面](http://stackoverflow.com/questions/8085188/ios-perform-action-after-period-of-inactivity-no-user-interaction/8994884#8994884)
* [第三方资源库](http://www.cocoachina.com/ios/20160719/17078.html)
* [状态栏提示](https://github.com/calimarkus/JDStatusBarNotification)
* [JSPatch基础用法总结](http://www.cocoachina.com/ios/20161202/18264.html)
* [视频录制压缩取帧](http://www.jianshu.com/p/6f23f608048e)
* mediaTypes的几种值及含义
```objc
const CFStringRef  kUTTypeMovie ;抽象的媒体格式（声音和视频）
const CFStringRef  kUTTypeVideo ;只有视频没有声音
const CFStringRef  kUTTypeAudio ;只有声音没有视频
```
* [ios10关于新机首次安装出现网络请求权限问题](http://www.cocoachina.com/ios/20161206/18304.html)
* [高仿微信](https://github.com/shorty-Man/GSD_WeiXin)
* [reactiveCocoa基本用法](https://gold.xitu.io/entry/57764bb65bbb5000593755c7)，[美团点评技术团队](http://tech.meituan.com/tag/ReactiveCocoa)
* arc4random_uniform(n)-->[0,n-1);
* [MLEmojiLabel](https://github.com/molon/MLEmojiLabel)
