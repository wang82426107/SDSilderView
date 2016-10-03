# SDSilderView
一款圆形的音量调节旋钮 ,UISilder的变种



![](http://upload-images.jianshu.io/upload_images/1396375-784abd17541807a2.gif?imageMogr2/auto-orient/strip)

</br>
####SDSilderView快速创建以及值的变化
***
SDSilderView创建非常的简单,我们只需要调用如下方法就可以快速创建SDSilderView了.
```
+(instancetype)initWithPosition:(CGPoint)positon viewRadius:(CGFloat)viewRadius;

```
因为SDSilderView整体是一个圆形,为了不必要的麻烦,我把SDSilderView的frame参数拆分成两部分,一部分是起始位置信息参数positon,另外一部分就是 它的半径参数viewRadius.创建示例如下所示.

```
    SDSilderView *silderView = [SDSilderView initWithPosition:CGPointMake(100, 100) viewRadius:100];
    
    [self.view addSubview: silderView];
```
