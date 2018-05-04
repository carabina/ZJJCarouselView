# ZJJCarouselView
###  How to use ZJJCarouselView

#### Installation with CocoaPods：pod 'ZJJCarouselView'

使用实例：
```
ZJJCarouselView *view = [[ZJJCarouselView alloc] initWithFrame:CGRectMake(0, 0, self.view.frame.size.width, 300)];
    view.imageUrls = @[
                       @"https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1525355773455&di=f396b05e29ab5f0e254ac8b748e0a927&imgtype=0&src=http%3A%2F%2Fimg5.duitang.com%2Fuploads%2Fitem%2F201502%2F13%2F20150213175601_GxesK.thumb.700_0.jpeg",
                       @"https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1525355773455&di=65b970d6cb5302a7cc3c20892133129b&imgtype=0&src=http%3A%2F%2Fimg3.duitang.com%2Fuploads%2Fitem%2F201605%2F19%2F20160519232035_zcSmh.jpeg",
                       @"https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1525355773454&di=7adeec6a3ee9ee3dae9ac69ff46f4648&imgtype=0&src=http%3A%2F%2Fimg3.duitang.com%2Fuploads%2Fitem%2F201608%2F01%2F20160801205410_vCTKn.thumb.700_0.jpeg",
                       @"https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1525355773453&di=c4d3bf6254515b07d6cf0669993a645f&imgtype=0&src=http%3A%2F%2Fimg4.duitang.com%2Fuploads%2Fitem%2F201508%2F22%2F20150822120345_r3vBk.jpeg"
                       ];
    
    [self.view addSubview:view];
    view.carouselViewdidSelectBlock = ^(NSInteger index) {
        
        NSLog(@"点击了第%ld张",index);
       
    };
    ```
