BCMagicTransition
=====================

![BCMagicTransition](https://github.com/boycechang/BCMagicTransition/blob/master/MagicTransition.gif)


## A MagicMove Style Custom UIViewController Transiton

### Version 1.0.0


---
If you like BCMagicTransition and use it, could you please:

 * star this repo 

 * send me some feedback. Thanks!


------------------------------------
Adding BCMagicTransition to your project
====================================

#### Requirements

* ARC only; iOS 7.0+

#### Get it as: 
##### 1) source files

1. Download the BCMagicTransition repository as a zip file or clone it
2. Copy the BCMagicTransition files into your Xcode project

##### 2) via Cocoa pods

BCMagicTransition is available on [CocoaPods](http://cocoapods.org). Just add the following to your project Podfile:

```ruby
pod 'BCMagicTransition'
```

If you want to read more about CocoaPods, have a look at [this short tutorial](http://www.raywenderlich.com/12139/introduction-to-cocoapods).


Basic usage
====================================
```objective-c
import "BCMagicTransitionViewController.h"

@interface MyViewController : BCMagicTransitionViewController


- (void)push
{
    ... ...
    
    [self pushViewController:secondVC fromViews:fromViews toViews:toViews duration:0.3];
}

```

-------

Misc
=======

Author: [Boyce Chang](http://www.boycechang.com)

-------
#### License
This code is distributed under the terms and conditions of the MIT license. 

-------
#### Contribution guidelines

If you are fixing a bug you discovered, please add also a unit test so I know how exactly to reproduce the bug before merging.
