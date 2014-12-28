# Android Studio介绍

Android Studio 是一个Android开发环境，基于IntelliJ IDEA. 类似 Eclipse ADT，Android Studio 提供了集成的 Android 开发工具用于开发和调试。


## 架构组成

在IDEA的基础上，Android Studio 提供了如下的功能特性。

* 基于Gradle的构建支持
* Android 专属的重构和快速修复
* 提示工具以捕获性能、可用性、版本兼容性等问题
* 支持ProGuard 和应用签名
* 基于模板的向导来生成常用的 Android 应用设计和组件
* 功能强大的布局编辑器，可以让你拖拉 UI 控件并进行效果预览

## 版本历史

下面是Android Studio版本发布的全部历史，按照最新的排序，可以从版本发布历史上看到其发展路线，更加详细的功能发布清单，请参考[官方的发布历史记录](http://tools.android.com/recent)。

* Android Studio v1.0.2 (Dec 18, 2014)
* Android Studio v1.0.1 (December 2014)
* Android Studio v1.0 (December 2014)
* Android Studio v0.8.14 (October 2014)
* Android Studio v0.8.6 (August 2014)
* Android Studio v0.8.0 (June 2014)
* Android Studio v0.5.2 (May 2014)
* Android Studio v0.4.6 (March 2014)
* Android Studio v0.4.2 (Jan 2014)
* Android Studio v0.3.2 (Oct 2013)
* Android Studio v0.2.x (July 2013)
* Android Studio v0.1.x (May 2013)


## Android Studio VS Eclipse

相信目前国内用Eclipse的还是大多数，那么首先就来说一下Studio的一些优点，比较才能更有说服力，才能说明为什么我们要从Eclipse迁移到Studio。

**1、Google推出的**
毫无疑问，这个是它的最大优势，Android Stuido是Google推出，专门为Android“量身订做”的，是Google大力支持的一款基于IntelliJ IDEA改造的IDE，这个应该能说明为什么它是Android的未来

**2、速度更快**
Eclipse的启动速度、响应速度、内存占用一直被诟病，相信大家这点应该深有体会，而且经常遇到卡死状态。Studio不管哪一个方面都全面领先Eclipse

**3、UI更漂亮**
I/O上演示的那款黑色主题真是太棒了，极客范，Stuido自带的Darcula主题的炫酷黑界面实在是高大上，相比而言Eclipse下的黑色主题太low了

**4、更加智能**
提示补全对于开发来说意义重大， Studio则更加智能，智能保存，从此再也不用每次都 Ctrl + S了。熟悉Studio以后效率会大大提升。

**5、整合了Gradle构建工具**
Gradle是一个新的构建工具，自Studio亮相之处就支持Gradle，可以说Gradle集合了Ant和Maven的优点，不管是配置、编译、打包都非常棒。

**6、强大的UI编辑器**
Android Studio的编辑器非常的智能，除了吸收Eclipse+ADT的优点之外，还自带了多设备的实时预览，相对这对Android开发者来说简直是神器啊。

**7、内置终端**
Studio内置终端，这对于习惯命令行操作的人来说简直是福音啊，再也不用来回切换了，一个Studio全部搞定。

**8、更完善的插件系统**
Studio下支持各种插件，如Git、Markdown、Gradle等等，你想要什么插件，直接搜索下载。

**9、完美整合版本控制系统**
安装的时候就自带了如GitHub, Git, SVN等流行的版本控制系统，可以直接check out你的项目。

大家看完以上是不是很动心呢，优点是很多，但是大家学习的时候会遇到很多问题，如Studio和Eclipse的目录结构、快捷键等等完全不一样，需要适应一段时间，Gradle同样增加了学习成本，虽然Google的更新速度已经相当快了，但是目前最新的是1.0RC版本，仍未推出正式版，说明可能会有一些小问题等，Studio官方解释暂未支持NDK，所以如果你的项目用到了NDK最好也不要使用Studio。

但是相信Google会越来越完善的，学习成本与适应阶段是我们做技术一直要保持的心态，一旦上手相信你要离不开它了。