# awesome-kotlin-android
[![Language](https://img.shields.io/badge/awesome-kotlin--android-blue.svg)](https://github.com/adisonhuang/awesome-kotlin-android)
[![PRS](https://img.shields.io/badge/PRS-welcome-yellow.svg)](https://github.com/adisonhuang/awesome-kotlin-android/pulls)
[![LICENSE](https://img.shields.io/badge/licenses-apache-green.svg)](http://www.apache.org/licenses/LICENSE-2.0)

<img src="xamarinkotlin.png" width="200">

## 关于

 本项目是一个专注于收集利用 Kotlin 进行 Android 开发的开源库，扩展，工具，开源项目，资料等高质量资源的集合

## 目录

   * [awesome-kotlin-android](#awesome-kotlin-android)
      * [开源库](#开源库)
         * [框架](#框架)
         * [DSL](#dsl)
         * [扩展](#扩展)
         * [UI](#ui)
            * [通用库](#通用库)
            * [Fragment](#fragment)
            * [动画](#动画)
            * [Toolbar](#toolbar)
            * [选择/过滤器](#选择过滤器)
            * [按钮](#按钮)
            * [进度条](#进度条)
            * [通知/提醒](#通知提醒)
            * [指示器](#指示器)
            * [特殊效果](#特殊效果)
            * [日历](#日历)
            * [其他](#其他)
         * [依赖注入](#依赖注入)
         * [数据绑定](#数据绑定)
         * [代理](#代理)
         * [数据库](#数据库)
         * [网络](#网络)
         * [日志](#日志)
         * [JSON](#json)
         * [函数式编程](#函数式编程)
         * [下载](#下载)
         * [图片](#图片)
         * [拍照](#拍照)
         * [指纹](#指纹)
         * [工具](#工具)
         * [其他](#其他-1)
         * [序列化](#序列化)
         * [测试](#测试)
      * [完整 app](#完整-app)
      * [DEMO](#demo)
      * [资料](#资料)
      * [其他](#其他-2)

```
 100+ Stars: 🔥
 200+ Stars: 🔥🔥
 500+ Stars: 🔥🔥🔥
1000+ Stars: 🔥🔥🔥🔥
2000+ Stars: 🔥🔥🔥🔥🔥

点击 ► 展示效果图
```


## 开源库
[back to top](#readme) 

### 框架
* [android-clean-architecture-boilerplate](https://github.com/bufferapp/android-clean-architecture-boilerplate) - clean 框架模板 🔥🔥🔥🔥🔥
* [Kotlin-Android-Template](https://github.com/nekocode/Kotlin-Android-Template) - 快速生成MVP 架构的项目模板 🔥🔥🔥🔥
* [KBinding](https://github.com/BennyWang/KBinding) - 使用kotlin实现的Android MVVM框架 🔥🔥

* [kotlin-android-starter](https://github.com/androidstarters/kotlin-android-starter) - 快速生成的android项目模板，基于MVP/Dagger2/RxJava2/Robolectric/Espresso/Mockito🔥🔥
   <details><summary><code>效果图</code>🔥🔥🔥</summary>
    <div style="display:flex;">
    <img alt="image" src="https://camo.githubusercontent.com/9172c7b3b586bb8599d25e0275b61a1d54e7a2ed/687474703a2f2f672e7265636f726469742e636f2f4c3573656c67376149762e676966" width="30%">
    <img alt="image" src="https://camo.githubusercontent.com/60f78409e29c214d20edd3e6bd7e59594072af0d/687474703a2f2f672e7265636f726469742e636f2f7874346f3577547953632e676966" width="50%">
   </details>

### DSL
* [anko](https://github.com/Kotlin/anko) - JetBrains 官方为Android编写的 DSL，旨在令开发 Android 更快更简单 🔥🔥🔥🔥🔥
* [MaterialDrawerKt](https://github.com/zsmb13/MaterialDrawerKt) - 不使用 XML 创建 Material Design 导航抽屉 🔥🔥
* [android-drawable-dsl](https://github.com/infotech-group/android-drawable-dsl) - 通过 kotlin 构造 drawable 而不是 XML 的 DSL 🔥

### 扩展

* [android-ktx](https://github.com/android/android-ktx) - google 开源的 Kotlin 扩展插件库，在 Android 框架和 Support Library 上提供相应 API 层，帮助开发者更自然编写 Kotlin 代码 🔥🔥🔥🔥🔥
* [KAndroid](https://github.com/pawegio/KAndroid) - 轻量级Kotlin 扩展插件库 🔥🔥🔥
* [kotlin-koi](https://github.com/mcxiaoke/kotlin-koi) - 又一个轻量级Kotlin 扩展插件库 🔥🔥
* [kotlin-jetpack](https://github.com/nsk-mironov/kotlin-jetpack) 有用的扩展方法集合 🔥

### UI

#### 通用库

* [anvil](https://github.com/zserge/anvil) - 一个受React启发的Android的最小UI库 🔥🔥🔥🔥

#### Fragment

* [FragNav](https://github.com/ncapdevi/FragNav) - 管理多个fragment 栈的库 🔥🔥🔥

#### 动画
* [transitioner](https://github.com/dev-labs-bg/transitioner) - 动态、简单的View场景切换动画
   <details><summary><code>效果图</code>🔥🔥🔥🔥</summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/dev-labs-bg/transitioner/raw/master/preview1.gif" width="50%">
   </details>
   
* [Konfetti](https://github.com/DanielMartinus/Konfetti) - 轻量五彩纸屑粒子系统
   <details><summary><code>效果图</code>🔥🔥🔥</summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/DanielMartinus/Konfetti/raw/master/media/konfetti_demo.gif" width="30%">
   </details>

#### Toolbar

* [JellyToolbar](https://github.com/Yalantis/JellyToolbar) - Yalantis出品，必属精品！炫酷 toolbar 实现
   <details><summary><code>效果图</code>🔥🔥🔥🔥</summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/Yalantis/JellyToolbar/raw/develop/gif.gif" width="50%">
   </details>

#### 选择/过滤器

* [SearchFilter](https://github.com/Yalantis/SearchFilter) - Yalantis出品，必属精品！炫酷 搜索过滤器 实现
   <details><summary><code>效果图</code>🔥🔥🔥🔥</summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/Yalantis/SearchFilter/raw/master/gif/dribbble.gif" width="50%">
   </details>
   
* [Multi-Selection](https://github.com/Yalantis/Multi-Selection) - Yalantis出品，必属精品！炫酷 多选器实现
   <details><summary><code>效果图</code>🔥🔥🔥🔥</summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/Yalantis/Multi-Selection/raw/develop/imgs/dribble.gif" width="50%">
   </details>

* [Bubble-Picker](https://github.com/igalata/Bubble-Picker) - 简单易用的漂浮球内容选择器
   <details><summary><code>效果图</code>🔥🔥🔥</summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/igalata/Bubble-Picker/raw/develop/shot.gif" width="50%">
   </details>
   
* [DateTimeRangePicker](https://github.com/skedgo/DateTimeRangePicker) - 日期时间范围选择器
   <details><summary><code>效果图</code>🔥🔥</summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/skedgo/DateTimeRangePicker/raw/master/images/Screenshot_1482250219.png" width="30%">
    <img alt="image" src="https://github.com/skedgo/DateTimeRangePicker/raw/master/images/Screenshot_1482250231.png" width="30%">
   </details>      

#### 按钮

* [Stepper-Touch](https://github.com/DanielMartinus/Stepper-Touch) - Material Design设计风格的触摸步进器
   <details><summary><code>效果图</code>🔥🔥</summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/DanielMartinus/Stepper-Touch/raw/master/media/demo.gif" width="30%">
   </details>
* [StickySwitch](https://github.com/GwonHyeok/StickySwitch) - 漂亮的切换开关
   <details><summary><code>效果图</code>🔥🔥</summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/GwonHyeok/StickySwitch/raw/master/preview.gif" width="30%">
   </details>   

#### 进度条

* [fluid-slider-android](https://github.com/Ramotion/fluid-slider-android) - 带有弹出式气泡的滑块进度条
   <details><summary><code>效果图</code>🔥🔥🔥</summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/Ramotion/fluid-slider-android/raw/master/Fluid-slider.gif" width="30%">
   </details>

#### 通知/提醒

* [Light](https://github.com/TonnyL/Light) - 优雅通用的 Snackbar
    <details><summary><code>效果图</code>🔥🔥</summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/TonnyL/Light/raw/master/images/success.png" width="30%">
     <img alt="image" src="https://github.com/TonnyL/Light/raw/master/images/info.png" width="30%">
     <img alt="image" src="https://github.com/TonnyL/Light/raw/master/images/warning.png" width="30%">
      </details>

#### 指示器

* [Android-Indefinite-Pager-Indicator](https://github.com/rbro112/Android-Indefinite-Pager-Indicator) -用于RecyclerView或ViewPager的轻量级、即插即用无限页面指示器
   <details><summary><code>效果图</code>🔥🔥🔥</summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/rbro112/Android-Indefinite-Pager-Indicator/raw/master/readme_assets/preview.gif" width="30%">
   </details> 

#### 特殊效果

* [shadow](https://github.com/loopeer/shadow) - 可以替代CardView的自定义阴影 view
   <details><summary><code>效果图</code>🔥🔥🔥</summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/loopeer/shadow/raw/master/screenshot/shadow_color.gif" width="30%">
    <img alt="image" src="https://github.com/loopeer/shadow/raw/master/screenshot/shadow_foreground.gif" width="30%">
   </details>

* [android-snowfall](https://github.com/JetradarMobile/android-snowfall) - 完全自定义实现的下雪效果
   <details><summary><code>效果图</code>🔥🔥🔥</summary>
    <div style="display:flex;">
    <img alt="image" src="https://raw.githubusercontent.com/JetradarMobile/android-snowfall/master/art/hotellook-demo.gif" width="30%">
   </details>

* [DroidArt](https://github.com/Cleveroad/DroidArt) - 在图像上键入任意形状的文本

   <details><summary><code>效果图</code>🔥</summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/Cleveroad/DroidArt/raw/master/images/demo.gif" width="50%">
   </details>   

#### 日历

* [LightCalendarView](https://github.com/recruit-mp/LightCalendarView) - 轻量级日历

   <details><summary><code>效果图</code>🔥🔥</summary>
    <div style="display:flex;">
    <img alt="image" src="https://cloud.githubusercontent.com/assets/21093614/18807459/a6692ca4-8282-11e6-921d-1ea46c545ed4.gif" width="30%">
   </details>

#### 其他

* [AdaptiveIconPlayground](https://github.com/nickbutcher/AdaptiveIconPlayground) - 一个体验 [adaptive icons](https://github.com/nickbutcher/AdaptiveIconPlayground)效果的应用
   <details><summary><code>效果图</code>🔥🔥🔥</summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/nickbutcher/AdaptiveIconPlayground/raw/master/screenshots/adaptive-icon-playground-demo.webp" width="30%">
   </details>

### 依赖注入

* [kotterknife](https://github.com/JakeWharton/kotterknife) - 基于ButterKnife 使用 kotlin编写的 Android 依赖注入框架 🔥🔥🔥🔥
* [koin](https://github.com/Ekito/koin) - 简明实用的 Kotlin 依赖注入框架 🔥🔥🔥
* [koin](https://github.com/Ekito/koin) - 没有代理，没有代码生成，没有反射；用简洁实用的方式编写依赖注入的轻量库。🔥🔥🔥
* [ActivityStarter](https://github.com/MarcinMoskala/ActivityStarter) Activity 启动生成器，更简单的方式传递多个参数 🔥🔥

### 数据绑定

* [LastAdapter](https://github.com/nitrico/LastAdapter) - 不需再写RecyclerView 的 adapter 和 ViewHolder 🔥🔥🔥

### 代理

* [Kotpref](https://github.com/chibatching/Kotpref) - SharedPreferences 代理库 🔥🔥

### 数据库

* [requery](https://github.com/requery/requery) - 轻量强大的ORM数据库 🔥🔥🔥🔥🔥
* [DBFlow](https://github.com/Raizlabs/DBFlow) - 一个健壮, 强大, 非常简单的 ORM android 数据库 🔥🔥🔥🔥🔥

### 网络

* [Fuel](https://github.com/kittinunf/Fuel) - 最简单的 HTTP 网络库 🔥🔥🔥🔥
* [http4k](https://github.com/http4k/http4k) - HTTP 工具包 🔥🔥

### 日志

* [OkLog](https://github.com/simonpercic/OkLog) - OkHttp的网络日志拦截器 🔥🔥
* [timberkt](https://github.com/ajalt/timberkt) - 基于Timber的日志库 🔥

### JSON

* [klaxon](https://github.com/cbeust/klaxon) - json 解析器🔥🔥🔥

### 函数式编程

* [RxKotlin](https://github.com/ReactiveX/RxKotlin) - RxJava 的 kotlin实现 🔥🔥🔥🔥🔥

### 下载

[RxDownload](https://github.com/ssseasonnn/RxDownload) - 基于RxJava的多线程下载工具 🔥🔥🔥🔥🔥

### 图片

* [clay](https://github.com/line/clay) - 图片自由裁剪库

### 拍照

* [Fotoapparat](https://github.com/Fotoapparat/Fotoapparat) - 友好的相机库 🔥🔥🔥🔥🔥

### 指纹

* [FingerprintManager](https://github.com/JesusM/FingerprintManager) - 简单的指纹处理库 🔥🔥🔥

### 工具
* [debug-bottle](https://github.com/kiruto/debug-bottle) - Android 开发调试工具 🔥🔥🔥
* [detekt](https://github.com/arturbosch/detekt) - 静态代码分析工具 🔥🔥🔥
* [Time](https://github.com/kizitonwose/Time) - 类型安全的时间库 🔥🔥🔥
* [fakeit](https://github.com/moove-it/fakeit) - 假数据生成库 🔥🔥
* [RxPay](https://github.com/Cuieney/RxPay) - 一个集成支付宝微信的支付工具  🔥🔥

### 其他
* [MapMe](https://github.com/TradeMe/MapMe) - 用于处理地图的 Android 库。MapMe 将适配器模式带入地图，简化了标记和注释的管理。🔥🔥🔥
* [Kovenant](https://github.com/mplatvoet/kovenant) - Kotlin 的 Promises 库 🔥🔥
* [paperparcel](https://github.com/grandstaish/paperparcel) - 自动生成Parcelable 代码的注解处理器 🔥🔥

### 序列化
* [kotlinx.serialization](https://github.com/Kotlin/kotlinx.serialization) - 跨平台序列化库。🔥🔥

### 测试
* [Barista](https://github.com/SchibstedSpain/Barista) - 基于Espresso的 UI 测试框架。🔥🔥


## 完整 app
[back to top](#readme) 
* [shadowsocks-android](https://github.com/shadowsocks/shadowsocks-android) - shadowsocks 客户端 🔥🔥🔥🔥🔥
* [Twidere-Android](https://github.com/TwidereProject/Twidere-Android) - Material Design 设计，功能完善的 Twitter 客户端 🔥🔥🔥🔥

* [Bandhook-Kotlin](https://github.com/antoniolg/Bandhook-Kotlin) - 音乐信息展示APP
   <details><summary><code>效果图</code>🔥🔥🔥🔥</summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/antoniolg/Bandhook-Kotlin/raw/master/art/bandhook.gif" width="30%">
    </div>
   </details>
   
* [tachiyomi](https://github.com/inorichi/tachiyomi) - 漫画阅读APP
   <details><summary><code>效果图</code>🔥🔥🔥🔥</summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/inorichi/tachiyomi/raw/master/.github/readme-images/screens.png" width="80%">
    </div>
   </details>

* [GankClient-Kotlin](https://github.com/githubwing/GankClient-Kotlin) - 用 Kotlin 写的 Gank 客户端
   <details><summary><code>效果图</code>🔥🔥🔥🔥</summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/githubwing/GankClient-Kotlin/raw/master/img/pic1.png" width="30%">
    <img alt="image" src="https://github.com/githubwing/GankClient-Kotlin/raw/master/img/pic2.png" width="30%">
    </div>
   </details>
* [Eyepetizer-in-Kotlin](https://github.com/LRH1993/Eyepetizer-in-Kotlin) - 数据来源自开眼视频的客户端
   <details><summary><code>效果图</code>🔥🔥🔥🔥</summary>
    <div style="display:flex;">
    <img alt="image" src="https://camo.githubusercontent.com/0f139856de508bd43a6bf5509f737e731580ff68/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f333938353536332d613432343664623833663833353837642e6a70673f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970253743696d61676556696577322f322f772f31323430" width="80%">
   </details>

*  [Kotlin-for-Android-Developers](https://github.com/antoniolg/Kotlin-for-Android-Developers) - 《Kotlin Android Developers》书籍的配套 APP 🔥🔥🔥🔥

* [tivi](https://github.com/chrisbanes/tivi) - 电视节目跟踪 APP 🔥🔥🔥🔥

* [Lightning-Browser](https://github.com/anthonycr/Lightning-Browser) - （闪电浏览器）是体积小巧的高性能浏览器 🔥🔥🔥🔥

* [Voice](https://github.com/PaulWoitaschek/Voice) - 有声电子书阅读器 🔥🔥🔥

* [PoiShuhui-Kotlin](https://github.com/wuapnjie/PoiShuhui-Kotlin) - 一个用 Kotlin 写的简单漫画 APP 
   <details><summary><code>效果图</code>🔥🔥🔥</summary>
    <div style="display:flex;">
    <img alt="image" src="http://7xrqmj.com1.z0.glb.clouddn.com/S60310-222037.jpg?imageView/2/w/300/q/90" width="30%">
    <img alt="image" src="http://7xrqmj.com1.z0.glb.clouddn.com/S60310-221942.jpg?imageView/2/w/300/q/90" width="30%">
    </div>
   </details>

* [Simple-Calendar](https://github.com/SimpleMobileTools/Simple-Calendar) - 日历 APP
   <details><summary><code>效果图</code>🔥🔥🔥</summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/SimpleMobileTools/Simple-Calendar/raw/master/fastlane/metadata/android/en-US/images/phoneScreenshots/app.png" width="30%">
    <img alt="image" src="https://github.com/SimpleMobileTools/Simple-Calendar/raw/master/fastlane/metadata/android/en-US/images/phoneScreenshots/app_5.png" width="30%">
    </div>
   </details>

* [conference-app-2018](https://github.com/DroidKaigi/conference-app-2018) - [DroidKaigi 2018](https://droidkaigi.jp/2018/en/)官方 app
   <details><summary><code>效果图</code>🔥🔥🔥</summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/DroidKaigi/conference-app-2018/raw/master/art/screenshot_sessions.png" width="30%">
    <img alt="image" src="https://github.com/DroidKaigi/conference-app-2018/raw/master/art/screenshot_search.png" width="30%">
    <img alt="image" src="https://github.com/DroidKaigi/conference-app-2018/raw/master/art/screenshot_session_detail.png" width="30%">
    </div>
   </details>

* [susi_android](https://github.com/fossasia/susi_android) - SUSI AI app，提供一个对话界面，使用loklak / AskSusi基础设施提供智能答案
   <details><summary><code>效果图</code>🔥🔥🔥</summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/fossasia/susi_android/raw/development/docs/_static/message.png" width="30%">
    <img alt="image" src="https://github.com/fossasia/susi_android/raw/development/docs/_static/voice_input.png" width="30%">
    <img alt="image" src="https://github.com/fossasia/susi_android/raw/development/docs/_static/skills.png" width="30%">
    </div>
   </details>
  
* [Tucao](https://github.com/blackbbc/Tucao) - 吐槽第三方Android客户端
    <details><summary><code>效果图</code>🔥🔥🔥</summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/blackbbc/Tucao/raw/master/art/1.gif" width="30%">
    <img alt="image" src="https://github.com/blackbbc/Tucao/raw/master/art/2.gif" width="30%">
    <img alt="image" src="https://github.com/blackbbc/Tucao/raw/master/art/3.gif" width="30%">
    </div>
    </details>

* [code-reader](https://github.com/loopeer/code-reader) - 代码阅读器，支持多种语言
    <details><summary><code>效果图</code>🔥🔥🔥</summary>
       <div style="display:flex;">
      <img alt="image" src="https://github.com/loopeer/code-reader/raw/master/screenshot/codereader_setting_day.gif" width="30%">
      <img alt="image" src="https://github.com/loopeer/code-reader/raw/master/screenshot/codereader_setting_night.gif" width="30%">
      </div>
    </details>

* [Ribble](https://github.com/armcha/Ribble) - Dribbble客户端

    <details><summary><code>效果图</code>🔥🔥🔥</summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/armcha/Ribble/raw/master/art/ribble_demo.gif" width="30%">
    </div>
    </details>
    
* [Mango](https://github.com/TonnyL/Mango) - Dribbble客户端

    <details><summary><code>效果图</code>🔥🔥🔥</summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/TonnyL/Mango/raw/master/art/Get-Started.png" width="30%">
    <img alt="image" src="https://github.com/TonnyL/Mango/raw/master/art/Main.png" width="30%">
    <img alt="image" src="https://github.com/TonnyL/Mango/raw/master/art/Shot.png" width="30%">
    </div>
    </details>    
    
* [CatchUp](https://github.com/hzsweers/CatchUp) - 聚合Hacker News、Reddit、Medium等平台的热门信息的 APP

    <details><summary><code>效果图</code>🔥🔥🔥</summary>
    <div style="display:flex;">
    <img alt="image" src="https://cdn-images-1.medium.com/max/1600/1*MlO6Y0bGIjjyTf-hmxR-zw.png" width="80%">
    </div>
    </details>

* [KedditBySteps](https://github.com/juanchosaravia/KedditBySteps) - Reddit客户端 🔥🔥🔥

* [Murmur](https://github.com/nekocode/Murmur) - 第三方豆瓣 FM 红心频道播放器🔥🔥
  
* [Simple-Gallery](https://github.com/SimpleMobileTools/Simple-Gallery) - 相册 APP
   <details><summary><code>效果图</code>🔥🔥</summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/SimpleMobileTools/Simple-Gallery/raw/master/fastlane/metadata/android/en-US/images/phoneScreenshots/app.jpg" width="30%">
    <img alt="image" src="https://github.com/SimpleMobileTools/Simple-Gallery/raw/master/fastlane/metadata/android/en-US/images/phoneScreenshots/app_2.jpg" width="30%">
    </div>
   </details>

* [Twobbble](https://github.com/550609334/Twobbble) - Dribbble客户端
   <details><summary><code>效果图</code>🔥🔥</summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/550609334/Twobbble/raw/master/image/image1.png?raw=true" width="30%">
    <img alt="image" src="https://github.com/550609334/Twobbble/raw/master/image/image2.png?raw=true" width="30%">
    </div>
   </details>

* [AndroidRivers](https://github.com/dodyg/AndroidRivers) - RSS阅读器 🔥🔥

* [Simple-Camera](https://github.com/SimpleMobileTools/Simple-Camera) - 拍照 APP
   <details><summary><code>效果图</code>🔥</summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/SimpleMobileTools/Simple-Camera/raw/master/fastlane/metadata/android/en-US/images/phoneScreenshots/app.jpg" width="30%">
    <img alt="image" src="https://github.com/SimpleMobileTools/Simple-Camera/raw/master/fastlane/metadata/android/en-US/images/phoneScreenshots/app_2.jpg" width="30%">
    </div>
   </details>

* [Simple-File-Manager](https://github.com/SimpleMobileTools/Simple-File-Manager) - 文件管理器
   <details><summary><code>效果图</code>🔥</summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/SimpleMobileTools/Simple-File-Manager/raw/master/fastlane/metadata/android/en-US/images/phoneScreenshots/app.png" width="30%">
    <img alt="image" src="https://github.com/SimpleMobileTools/Simple-File-Manager/raw/master/fastlane/metadata/android/en-US/images/phoneScreenshots/app_2.png" width="30%">
    </div>
   </details>

* [饭否精选](https://github.com/TonnyL/FanfouHandpick) - 使用 Kotlin 开发的饭否精选 App
   <details><summary><code>效果图</code>🔥</summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/marktony/FanfouHandpick/raw/master/screenshots/0.png" width="30%">
    </div>
   </details>
  
* [KotlinMvp](https://github.com/git-xuhao/KotlinMvp) -  基于Kotlin+MVP+Retrofit+RxJava+Glide 等架构实现的短视频类的APP
    <details><summary><code>效果图</code></summary>
       <div style="display:flex;">
      <img alt="image" src="https://github.com/git-xuhao/KotlinMvp/raw/master/screenshot/kotlin-mvp-1.gif" width="30%">
      </div>
    </details>

* [Simple-Notes](https://github.com/SimpleMobileTools/Simple-Notes) - 便签 APP
   <details><summary><code>效果图</code></summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/SimpleMobileTools/Simple-Notes/raw/master/fastlane/metadata/android/en-US/images/phoneScreenshots/app.png" width="30%">
    <img alt="image" src="https://github.com/SimpleMobileTools/Simple-Notes/raw/master/fastlane/metadata/android/en-US/images/phoneScreenshots/app_2.png" width="30%">
    </div>
   </details>  

## DEMO
[back to top](#readme) 

* [android-topeka](https://github.com/googlesamples/android-topeka) - google 官方 material design 示例应用 

    <details><summary><code>效果图</code>🔥🔥🔥🔥🔥</summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/googlesamples/android-topeka/raw/master/screenshots/categories.png" width="30%">
    <img alt="image" src="https://github.com/googlesamples/android-topeka/raw/master/screenshots/category_history.png" width="30%">
    </div>
    </details>

* [kotlin-dagger-example](https://github.com/damianpetla/kotlin-dagger-example) - Dagger 2 和 Kotlin 结合例子 🔥🔥

* [kotlin-fullstack-sample](https://github.com/Kotlin/kotlin-fullstack-sample) - kotlin 全栈开发应用例子，包括前端和后台 🔥🔥🔥


## 资料
[back to top](#readme) 

* [Kotlin for android developers中文翻译](https://github.com/wangjiegulu/kotlin-for-android-developers-zh) 🔥🔥🔥🔥🔥
* [Kotlin-Tutorials](https://github.com/enbandari/Kotlin-Tutorials) - Kotlin 视频教程 🔥🔥🔥🔥🔥

## 其他
[back to top](#readme) 

* [WechatMagician](https://github.com/Gh0u1L5/WechatMagician) - Xposed插件，致力于让用户彻底掌控微信上的聊天消息及朋友圈内容，支持微信 6.5.3 及以上版本 🔥🔥🔥








```

```