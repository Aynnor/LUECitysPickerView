# LUECitysPickerView
中国城市地址选择器View

地址列表PickerView

```Objective-C

//必须使用initWihtFrame:方法去创建, 不要alloc init

示例代码:
  CGFloat viewHeight = 220;
    
    UIAddressPickerView *address = [[UIAddressPickerView alloc] initWithFrame:CGRectMake(0, self.view.bounds.size.height - viewHeight, self.view.bounds.size.width, viewHeight)];
    _address = address;
    address.delegate = self;
    
    [address setPickerViewHeight:300 titleViewHeight:50];//调整titleView和本View高度
    [self.view addSubview:address];


```
