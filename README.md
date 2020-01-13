# SizeClasses
Size Classes 为 iOS 8 的新特性，其特点就是将各个设备屏幕及其旋转后状态都抽象成屏幕Size的变化，而不再关心具体的尺寸。具体就是将屏幕的宽度抽象成Compact（紧凑型）、Any（任意）、Regular（常规）三种情况，高度也是如此，因此就有9种情况。简单的说，就是在一个Storyboard或者xib上，能够管理9种类型的视图。
