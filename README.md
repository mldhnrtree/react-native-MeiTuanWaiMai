# react-native-MeiTuanWaiMai

基于React-Native仿美团外卖App

*Mock数据采取非正常手段获取，请不要在其他地方使用*

# 运行截图
<div align="center">
<img src="https://github.com/mldhnrtree/react-native-MeiTuanWaiMai/raw/master/screenshots/home.jpg" height="360" />
<img src="https://github.com/mldhnrtree/react-native-MeiTuanWaiMai/raw/master/screenshots/orders.jpg" height="360" />
<img src="https://github.com/mldhnrtree/react-native-MeiTuanWaiMai/raw/master/screenshots/order_eval.png" height="360" />
</div>
<div align="center">
<img src="https://github.com/mldhnrtree/react-native-MeiTuanWaiMai/raw/master/screenshots/order_refund.png" height="360" />
<img src="https://github.com/mldhnrtree/react-native-MeiTuanWaiMai/raw/master/screenshots/mine.jpg" height="360" />
<img src="https://github.com/mldhnrtree/react-native-MeiTuanWaiMai/raw/master/screenshots/share.jpg" height="360" />
</div>

# 待完善界面

- 搜索
- 定位
- 商家
- 分类
- Mock Server
- ...

# 安装

    npm install
    
    react-native link
    
    react-native run-android
## 已知错误

- 升级RN至0.52版本后，react-native-vector-icons会报如下错误，请参考[react-native-vector-icons#626](https://github.com/oblador/react-native-vector-icons/issues/626)

    error: bundling failed: Error: While resolving module `react-native-vector-icons/Ionicons`, the Haste package `react-native-vector-icons` was found. However the module `Ionicons` could
    not be found within the package. Indeed, none of these files exist


# 第三方依赖库

[react-native-swiper](https://github.com/leecade/react-native-swiper)

[react-native-vector-icons](https://github.com/oblador/react-native-vector-icons)

[react-navigation](https://github.com/react-navigation/react-navigation)