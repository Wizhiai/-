# -
对数字尾巴UI进行的高仿，正文页使用了重写的uiwebview，并对label字体进行了自适应
高仿数字尾巴的首页UI，并对正文页进行了伪数据模拟，使用了uiwebview，为使其更加贴近真实项目，
对label进行了字数自适应，会根绝字的多少自动调整label的frame。uiwebview里只有一个子控件uiscrollview,
为了使页面整体更协调，我对webview的子控件进行了遍历,使用 [NSArray arrayWithArray:[self.webview subviews]]，
(UIView *)[sv objectAtIndex:0]将其强制转换成uiview，以方便布局。uitableview使用了自定义cell,
在布局方面使用了切角画切圆等技巧使cell更加美观。数据处理方面初次尝试了FMDB管理sqlite.
有问题建议可联系QQ：630806244
![image](http://foru.oss-cn-hangzhou.aliyuncs.com/ForUDoc%2Fshuziweiba.gif)  
