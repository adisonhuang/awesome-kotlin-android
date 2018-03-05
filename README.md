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
            * [动画](#动画)
            * [Toolbar](#toolbar)
            * [选择/过滤器](#选择过滤器)
            * [按钮](#按钮)
            * [特殊效果](#特殊效果)
            * [其他](#其他)
         * [依赖注入](#依赖注入)
         * [数据绑定](#数据绑定)
         * [代理](#代理)
         * [数据库](#数据库)
         * [网络](#网络)
         * [日志](#日志)
         * [函数式编程](#函数式编程)
         * [下载](#下载)
         * [图片](#图片)
         * [拍照](#拍照)
         * [工具](#工具)
         * [其他](#其他)

      * [完整 app](#完整-app)

      * [DEMO](#demo)

      * [资料](#资料)

```
点击 ► 展示效果图
```


## 开源库
[back to top](#readme) 

### 框架

* [KBinding](https://github.com/EndSmile/KBinding) - 使用kotlin实现的Android MVVM框架
* [Kotlin-Android-Template](https://github.com/nekocode/Kotlin-Android-Template) - 快速生成MVP 架构的项目模板
* [android-clean-architecture-boilerplate](https://github.com/bufferapp/android-clean-architecture-boilerplate) - clean 框架模板

### DSL
* [anko](https://github.com/Kotlin/anko) - JetBrains 官方为Android编写的 DSL，旨在令开发 Android 更快更简单
* [android-drawable-dsl](https://github.com/infotech-group/android-drawable-dsl) - 通过 kotlin 构造 drawable 而不是 XML 的 DSL
* [MaterialDrawerKt](https://github.com/zsmb13/MaterialDrawerKt) - 不使用 XML 创建 Material Design 导航抽屉 

### 扩展

* [android-ktx](https://github.com/android/android-ktx) - google 开源的 Kotlin 扩展插件库，在 Android 框架和 Support Library 上提供相应 API 层，帮助开发者更自然编写 Kotlin 代码
* [KAndroid](https://github.com/pawegio/KAndroid) - 轻量级Kotlin 扩展插件库
* [kotlin-jetpack](https://github.com/nsk-mironov/kotlin-jetpack) 有用的扩展方法集合
* [kotlin-koi](https://github.com/mcxiaoke/kotlin-koi) - 又一个轻量级Kotlin 扩展插件库

### UI

#### 通用库

* [anvil](https://github.com/zserge/anvil) - 一个受React启发的Android的最小UI库

#### 动画

* [Konfetti](https://github.com/DanielMartinus/Konfetti) - 轻量五彩纸屑粒子系统
   <details><summary><code>效果图</code></summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/DanielMartinus/Konfetti/raw/master/media/konfetti_demo.gif" width="30%">
   </details>

* [transitioner](https://github.com/dev-labs-bg/transitioner) - 动态、简单的View场景切换动画
   <details><summary><code>效果图</code></summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/dev-labs-bg/transitioner/raw/master/preview1.gif" width="50%">
   </details>

#### Toolbar

* [JellyToolbar](https://github.com/Yalantis/JellyToolbar) - Yalantis出品，必属精品！炫酷 toolbar 实现
   <details><summary><code>效果图</code></summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/Yalantis/JellyToolbar/raw/develop/gif.gif" width="50%">
   </details>
  
#### 选择/过滤器

* [SearchFilter](https://github.com/Yalantis/SearchFilter) - Yalantis出品，必属精品！炫酷 搜索过滤器 实现
   <details><summary><code>效果图</code></summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/Yalantis/SearchFilter/raw/master/gif/dribbble.gif" width="50%">
   </details>
   
* [Multi-Selection](https://github.com/Yalantis/Multi-Selection) - Yalantis出品，必属精品！炫酷 多选器实现
   <details><summary><code>效果图</code></summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/Yalantis/Multi-Selection/raw/develop/imgs/dribble.gif" width="50%">
   </details>

* [Bubble-Picker](https://github.com/igalata/Bubble-Picker) - 简单易用的漂浮球内容选择器
   <details><summary><code>效果图</code></summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/igalata/Bubble-Picker/raw/develop/shot.gif" width="50%">
   </details>

#### 按钮

* [Stepper-Touch](https://github.com/DanielMartinus/Stepper-Touch) - Material Design设计风格的触摸步进器
   <details><summary><code>效果图</code></summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/DanielMartinus/Stepper-Touch/raw/master/media/demo.gif" width="30%">
   </details>

#### 特殊效果

* [shadow](https://github.com/loopeer/shadow) - 可以替代CardView的自定义阴影 view
   <details><summary><code>效果图</code></summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/loopeer/shadow/raw/master/screenshot/shadow_color.gif" width="30%">
    <img alt="image" src="https://github.com/loopeer/shadow/raw/master/screenshot/shadow_foreground.gif" width="30%">
   </details>

* [android-snowfall](https://github.com/JetradarMobile/android-snowfall) - 完全自定义实现的下雪效果
   <details><summary><code>效果图</code></summary>
    <div style="display:flex;">
    <img alt="image" src="https://raw.githubusercontent.com/JetradarMobile/android-snowfall/master/art/hotellook-demo.gif" width="30%">
   </details>
   
#### 其他

* [AdaptiveIconPlayground](https://github.com/nickbutcher/AdaptiveIconPlayground) - 一个体验 [adaptive icons](https://github.com/nickbutcher/AdaptiveIconPlayground)效果的应用
   <details><summary><code>效果图</code></summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/nickbutcher/AdaptiveIconPlayground/raw/master/screenshots/adaptive-icon-playground-demo.webp" width="30%">
   </details>

### 依赖注入

* [kotterknife](https://github.com/JakeWharton/kotterknife) - 基于ButterKnife 使用 kotlin编写的 Android 依赖注入框架
* [koin](https://github.com/Ekito/koin) - 简明实用的 Kotlin 依赖注入框架
* [ActivityStarter](https://github.com/MarcinMoskala/ActivityStarter) Activity 启动生成器，更简单的方式传递多个参数
* [koin](https://github.com/Ekito/koin) - 没有代理，没有代码生成，没有反射；用简洁实用的方式编写依赖注入的轻量库。

### 数据绑定

* [LastAdapter](https://github.com/nitrico/LastAdapter) - 不需再写RecyclerView 的 adapter 和 ViewHolder

### 代理

* [Kotpref](https://github.com/chibatching/Kotpref) - SharedPreferences 代理库

### 数据库

* [requery](https://github.com/requery/requery) - 轻量强大的ORM数据库
* [DBFlow](https://github.com/Raizlabs/DBFlow) - 一个健壮, 强大, 非常简单的 ORM android 数据库

### 网络

* [Fuel](https://github.com/kittinunf/Fuel) - 最简单的 HTTP 网络库

### 日志

* [timberkt](https://github.com/ajalt/timberkt) - 基于Timber的日志库

### 函数式编程

* [RxKotlin](https://github.com/ReactiveX/RxKotlin) - RxJava 的 kotlin实现

### 下载

[RxDownload](https://github.com/ssseasonnn/RxDownload) - 基于RxJava的多线程下载工具

### 图片

* [clay](https://github.com/line/clay) - 图片自由裁剪库



### 拍照

* [Fotoapparat](https://github.com/Fotoapparat/Fotoapparat) - 友好的相机库

### 工具

* [fakeit](https://github.com/moove-it/fakeit) - 假数据生成库
* [debug-bottle](https://github.com/kiruto/debug-bottle) - Android 开发调试工具
* [detekt](https://github.com/arturbosch/detekt) - 静态代码分析工具

### 其他

* [Kovenant](https://github.com/mplatvoet/kovenant) - Kotlin 的 Promises 库
* [paperparcel](https://github.com/grandstaish/paperparcel) - 自动生成Parcelable 代码的注解处理器
* [MapMe](https://github.com/TradeMe/MapMe) - 用于处理地图的 Android 库。MapMe 将适配器模式带入地图，简化了标记和注释的管理。



## 完整 app
[back to top](#readme) 

* [PoiShuhui-Kotlin](https://github.com/wuapnjie/PoiShuhui-Kotlin) - 一个用 Kotlin 写的简单漫画 APP
   <details><summary><code>效果图</code></summary>
    <div style="display:flex;">
    <img alt="image" src="http://7xrqmj.com1.z0.glb.clouddn.com/S60310-222037.jpg?imageView/2/w/300/q/90" width="30%">
    <img alt="image" src="http://7xrqmj.com1.z0.glb.clouddn.com/S60310-221942.jpg?imageView/2/w/300/q/90" width="30%">
    </div>
   </details>

* [Bandhook-Kotlin](https://github.com/antoniolg/Bandhook-Kotlin) - 音乐信息展示APP
   <details><summary><code>效果图</code></summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/antoniolg/Bandhook-Kotlin/raw/master/art/bandhook.gif" width="30%">
    </div>
   </details>

* [tachiyomi](https://github.com/inorichi/tachiyomi) - 漫画阅读APP
   <details><summary><code>效果图</code></summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/inorichi/tachiyomi/raw/master/.github/readme-images/screens.png" width="80%">
    </div>
   </details>

* [Simple-Calendar](https://github.com/SimpleMobileTools/Simple-Calendar) - 日历 APP
   <details><summary><code>效果图</code></summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/SimpleMobileTools/Simple-Calendar/raw/master/fastlane/metadata/android/en-US/images/phoneScreenshots/app.png" width="30%">
    <img alt="image" src="https://github.com/SimpleMobileTools/Simple-Calendar/raw/master/fastlane/metadata/android/en-US/images/phoneScreenshots/app_5.png" width="30%">
    </div>
   </details>

* [Simple-Camera](https://github.com/SimpleMobileTools/Simple-Camera) - 拍照 APP
   <details><summary><code>效果图</code></summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/SimpleMobileTools/Simple-Camera/raw/master/fastlane/metadata/android/en-US/images/phoneScreenshots/app.jpg" width="30%">
    <img alt="image" src="https://github.com/SimpleMobileTools/Simple-Camera/raw/master/fastlane/metadata/android/en-US/images/phoneScreenshots/app_2.jpg" width="30%">
    </div>
   </details>

* [Simple-File-Manager](https://github.com/SimpleMobileTools/Simple-File-Manager) - 文件管理器
   <details><summary><code>效果图</code></summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/SimpleMobileTools/Simple-File-Manager/raw/master/fastlane/metadata/android/en-US/images/phoneScreenshots/app.png" width="30%">
    <img alt="image" src="https://github.com/SimpleMobileTools/Simple-File-Manager/raw/master/fastlane/metadata/android/en-US/images/phoneScreenshots/app_2.png" width="30%">
    </div>
   </details>

* [Simple-Gallery](https://github.com/SimpleMobileTools/Simple-Gallery) - 相册 APP
   <details><summary><code>效果图</code></summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/SimpleMobileTools/Simple-Gallery/raw/master/fastlane/metadata/android/en-US/images/phoneScreenshots/app.jpg" width="30%">
    <img alt="image" src="https://github.com/SimpleMobileTools/Simple-Gallery/raw/master/fastlane/metadata/android/en-US/images/phoneScreenshots/app_2.jpg" width="30%">
    </div>
   </details>

* [Simple-Notes](https://github.com/SimpleMobileTools/Simple-Notes) - 便签 APP
   <details><summary><code>效果图</code></summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/SimpleMobileTools/Simple-Notes/raw/master/fastlane/metadata/android/en-US/images/phoneScreenshots/app.png" width="30%">
    <img alt="image" src="https://github.com/SimpleMobileTools/Simple-Notes/raw/master/fastlane/metadata/android/en-US/images/phoneScreenshots/app_2.png" width="30%">
    </div>
   </details>

* [GankClient-Kotlin](https://github.com/githubwing/GankClient-Kotlin) - 用 Kotlin 写的 Gank 客户端
   <details><summary><code>效果图</code></summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/githubwing/GankClient-Kotlin/raw/master/img/pic1.png" width="30%">
    <img alt="image" src="https://github.com/githubwing/GankClient-Kotlin/raw/master/img/pic2.png" width="30%">
    </div>
   </details>

* [饭否精选](https://github.com/TonnyL/FanfouHandpick) - 使用 Kotlin 开发的饭否精选 App
   <details><summary><code>效果图</code></summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/marktony/FanfouHandpick/raw/master/screenshots/0.png" width="30%">
    </div>
   </details>

* [Eyepetizer-in-Kotlin](https://github.com/LRH1993/Eyepetizer-in-Kotlin) - 数据来源自开眼视频的客户端
   <details><summary><code>效果图</code></summary>
    <div style="display:flex;">
    <img alt="image" src="https://camo.githubusercontent.com/0f139856de508bd43a6bf5509f737e731580ff68/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f333938353536332d613432343664623833663833353837642e6a70673f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970253743696d61676556696577322f322f772f31323430" width="80%">
   </details>

* [conference-app-2018](https://github.com/DroidKaigi/conference-app-2018) - [DroidKaigi 2018](https://droidkaigi.jp/2018/en/)官方 app
   <details><summary><code>效果图</code></summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/DroidKaigi/conference-app-2018/raw/master/art/screenshot_sessions.png" width="30%">
    <img alt="image" src="https://github.com/DroidKaigi/conference-app-2018/raw/master/art/screenshot_search.png" width="30%">
    <img alt="image" src="https://github.com/DroidKaigi/conference-app-2018/raw/master/art/screenshot_session_detail.png" width="30%">
    </div>
   </details>

* [susi_android](https://github.com/fossasia/susi_android) - SUSI AI app，提供一个对话界面，使用loklak / AskSusi基础设施提供智能答案
   <details><summary><code>效果图</code></summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/fossasia/susi_android/raw/development/docs/_static/message.png" width="30%">
    <img alt="image" src="https://github.com/fossasia/susi_android/raw/development/docs/_static/voice_input.png" width="30%">
    <img alt="image" src="https://github.com/fossasia/susi_android/raw/development/docs/_static/skills.png" width="30%">
    </div>
   </details>
  
* [Tucao](https://github.com/blackbbc/Tucao) - 吐槽第三方Android客户端
    <details><summary><code>效果图</code></summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/blackbbc/Tucao/raw/master/art/1.gif" width="30%">
    <img alt="image" src="https://github.com/blackbbc/Tucao/raw/master/art/2.gif" width="30%">
    <img alt="image" src="https://github.com/blackbbc/Tucao/raw/master/art/3.gif" width="30%">
    </div>
    </details>
  
* [KotlinMvp](https://github.com/git-xuhao/KotlinMvp) -  基于Kotlin+MVP+Retrofit+RxJava+Glide 等架构实现的短视频类的APP
    <details><summary><code>效果图</code></summary>
       <div style="display:flex;">
      <img alt="image" src="https://github.com/git-xuhao/KotlinMvp/raw/master/screenshot/kotlin-mvp-1.gif" width="30%">
      </div>
    </details>
  
* [CatchUp](https://github.com/hzsweers/CatchUp) - 聚合Hacker News、Reddit、Medium等平台的热门信息的 APP

    <details><summary><code>效果图</code></summary>
    <div style="display:flex;">
    <img alt="image" src="https://cdn-images-1.medium.com/max/1600/1*MlO6Y0bGIjjyTf-hmxR-zw.png" width="80%">
    </div>
    </details>
  
* [code-reader](https://github.com/loopeer/code-reader) - 代码阅读器，支持多种语言
    <details><summary><code>效果图</code></summary>
       <div style="display:flex;">
      <img alt="image" src="https://github.com/loopeer/code-reader/raw/master/screenshot/codereader_setting_day.gif" width="30%">
      <img alt="image" src="https://github.com/loopeer/code-reader/raw/master/screenshot/codereader_setting_night.gif" width="30%">
      </div>
    </details>

* [Ribble](https://github.com/armcha/Ribble) - Dribbble客户端

    <details><summary><code>效果图</code></summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/armcha/Ribble/raw/master/art/ribble_demo.gif" width="30%">
    </div>
    </details>

*  [Kotlin-for-Android-Developers](https://github.com/antoniolg/Kotlin-for-Android-Developers) - 《Kotlin Android Developers》书籍的配套 APP

* [AndroidRivers](https://github.com/dodyg/AndroidRivers) - RSS阅读器
* [tivi](https://github.com/chrisbanes/tivi) - 电视节目跟踪 APP

* [Lightning-Browser](https://github.com/anthonycr/Lightning-Browser) - （闪电浏览器）是体积小巧的高性能浏览器

* [Voice](https://github.com/PaulWoitaschek/Voice) - 有声电子书阅读器
* [shadowsocks-android](https://github.com/shadowsocks/shadowsocks-android) - shadowsocks 客户端
* [Twidere-Android](https://github.com/TwidereProject/Twidere-Android) - Material Design 设计，功能完善的 Twitter 客户端


## DEMO
[back to top](#readme) 

* [android-topeka](https://github.com/googlesamples/android-topeka) - google 官方 material design 示例应用

    <details><summary><code>效果图</code></summary>
    <div style="display:flex;">
    <img alt="image" src="https://github.com/googlesamples/android-topeka/raw/master/screenshots/categories.png" width="30%">
    <img alt="image" src="https://github.com/googlesamples/android-topeka/raw/master/screenshots/category_history.png" width="30%">
    </div>
    </details>

* [kotlin-dagger-example](https://github.com/damianpetla/kotlin-dagger-example) - Dagger 2 和 Kotlin 结合例子

* [kotlin-fullstack-sample](https://github.com/Kotlin/kotlin-fullstack-sample) - kotlin 全栈开发应用例子，包括前端和后台


## 资料
[back to top](#readme) 

* [Kotlin for android developers中文翻译](https://github.com/wangjiegulu/kotlin-for-android-developers-zh)
* [Kotlin-Tutorials](https://github.com/enbandari/Kotlin-Tutorials) - Kotlin 视频教程







