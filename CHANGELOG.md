## 2.2.9


修复 uluGameSDK 和 uluVersionUpdater资源找不到问题


## 2.2.8


改变依赖方式

升级第三方版本：

```
spec.dependency 'Firebase/Analytics', '~> 8.3.0'
  spec.dependency 'Firebase/Messaging', '~> 8.3.0'
  spec.dependency 'FBSDKCoreKit', '~> 11.0.1'
  spec.dependency 'FBSDKLoginKit', '~> 11.0.1'
  spec.dependency 'FBSDKShareKit', '~> 11.0.1'
  spec.dependency 'Masonry', '~> 1.1.0'
  spec.dependency 'ProgressHUD', '~> 2.7'
  spec.dependency 'MBProgressHUD', '~> 1.1.0'
  spec.dependency 'DGActivityIndicatorView', '~> 2.1.1'
  spec.dependency 'BEMCheckBox', '~> 1.4.1'
  spec.dependency 'GoogleSignIn', '~> 5.0.2'
  spec.dependency 'GBDeviceInfo', '~> 6.6.0'
  spec.dependency 'UIButton-SSEdgeInsets', '~> 0.1.7'
  spec.dependency 'TDOAuth' , '~> 1.3.0'
  spec.dependency 'FMDB', '~> 2.7.5'

  #Banner only frameworks
  spec.dependency 'YYModel', '~> 1.0.4'
  spec.dependency 'SDWebImage', '~> 3.8.3'

  #Statistics
  #pod 'PromisesObjC', '1.2'
  #pod 'Fabric', '~>1.10.2'
  #pod 'Crashlytics' , '~> 3.14.0'


  spec.dependency 'AFNetworking', '~> 4.0.1'
  spec.dependency 'AFNetworking+RetryPolicy', '~> 2.0.0'
  spec.dependency 'UICKeyChainStore', '~> 2.1.2'
```
