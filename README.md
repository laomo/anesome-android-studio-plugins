##  Android Studio Plugins

Android Studio(以下简称AS)插件可以极大的提高开发效率，解放我们的双手，以下是使用过程中收集的插件。由于AS基于IntelliJ IDEA，所以插件其实是通用的。

### 关于安装
1. Download and install `The Plugin` directly from Intellij / Android Studio: Preferences/Settings->Plugins->Browse Repositories

2. Alternatively, you can dowload `The Plugin` and install it manually in: Preferences/Settings->Plugins->Install plugin from disk

以下如果没有提供相应连接(`no link`)，可以直接通过方法 `1` 安装

### 代码生成类
#### ButterKnifeZelezny
Simple plug-in for Android Studio/IDEA that allows one-click creation of `Butterknife` view injections.

https://github.com/avast/android-butterknife-zelezny

#### SelectorChapek for Android
This Android Studio plugin automatically generates `drawable selectors` from appropriately named Android resources.

https://github.com/inmite/android-selector-chapek

#### GsonFormat

根据Gson库使用的要求,将JSONObject格式的String 解析成实体

https://github.com/zzz40500/GsonFormat

Model类必不可少，写起来没什么技术含量，这个插件非常不错。不过相比之下，个人更喜欢接下来的这个～

#### Lombok Plugin for IntelliJ IDEA
Provides support for `lombok` annotations to write great Java code with IntelliJ IDEA.

https://github.com/mplushnikov/lombok-intellij-plugin

这里此插件只是辅助作用，其实主角是 `Lombok` 。简单来说，Lombok 就是通过先注解然后编译时生成相关代码, 比如 getter 和 setter 方法等。

想了解更多请先移步官网：
https://projectlombok.org/

在 Android 开发中如何使用：https://projectlombok.org/setup/android.html

####  AndroidManifestFitter
Plugin for Intellij and Android Studio to add the activity to the AndroidManifest

https://github.com/JorgeDC/AndroidManifestFitter

README实在是。。看起来作者主要是自用。不过在 `stackoverflow` 上作者 [JorgeDeCorte](https://stackoverflow.com/users/1145289/jorgedecorte) 有详细的说明：

https://stackoverflow.com/questions/6640067/automatically-add-activity-to-manifest

When you have an Activity or a class that inherits from Activity at some point that has no mention in the AndroidManifest.xml you can press (`CMD/CTRL+N`) and press `add to manifest`. This adds the activity to the manifest.

https://dl.dropboxusercontent.com/u/3491432/AndroidManifestFitter.jar

### 功能类
### eventbus-intellij-plugin
Plugin to navigate between events posted by [EventBus](https://github.com/greenrobot/EventBus).

https://github.com/kgmyshin/eventbus-intellij-plugin
### ADB相关的插件

#### Adb Uninstall
Provides simple visual uninstalling support for the current application.

通过Icon 菜单直接卸载App

`no link`

#### ADB Idea
A plugin for Android Studio and Intellij IDEA that speeds up your day to day android development.

The following commands are provided:

* Uninstall App
* Kill App
* Start App
* Restart App
* Clear App Data
* Clear App Data and Restart

相比之下这个功能更强大，不过需要用过子菜单进行操作，当然完全可以自定义快捷键提高效率。

https://github.com/pbreault/adb-idea

#### Android Intent Sender

Plugin allows you to send intents with specified data and extras to android devices or emulators with the ADB command "broadcast", "startactivity", "startservice".  
Typical plugin use-cases:
 1. Broadcast receivers testing (including intent filters testing for custom data schemes, mime-types and so on)
 2. Starting activities which are deep withing an app flow (even not exported ones)
 3. Launching services from the IDE
 4. Testing receivers, activities and services with different intent extras
 5. ...

https://github.com/WeezLabs/idea-intent-sender-plugin

#### Android WiFi ADB
IntelliJ/AndroidStudio plugin which provides a button to connect your Android device over WiFi to install, run and debug your applications without a USB connected.

https://github.com/pedrovgs/AndroidWiFiADB

#### 更多插件
AS->Preferences/Settings->Plugins->Browse Repositories-Search What you want

####  DIY : Creating Your Plugin
http://www.jetbrains.org/intellij/sdk/docs/basics/getting_started.html
