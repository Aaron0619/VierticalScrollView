# VierticalScrollView
仿照淘宝头条竖直滚动效果
====
使用方法：
-------
```objc
NSArray *dataTypeArray = @[@"类型1",@"类型2",@"类型3",@"类型4",@"类型5"];
NSArray *dataTitleArray = @[@"默认标题1",@"默认标题2",@"默认标题3",@"默认标题4",@"默认标题5"];
VierticalScrollView *rollView = [[VierticalScrollView alloc] initWithFrame:CGRectMake(CGRectGetMaxX(imageV.frame), 100, self.view.frame.size.width, 60)];
[rollView setDataWithArray:dataTypeArray AndTitleArray:dataTitleArray];
[self.view addSubview:rollView];
