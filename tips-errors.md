# Android Studio 常见错误&解决办法


## SDK 无法更新解决方案

这个问题不是Android Studio的问题，而且由一些一些众所周知的原因导致的，我们这里说下解决办法。

打开**SDK Manager**，停止更新连接；在界面上方找`Tools->Options`打开了SDK Manager的`Settings`，选中`“Force https://… sources to be fetched using http://…”`，强制使用http协议,然后还需要按照下面步骤配置下hosts。

首先，找到你的hosts文件，不同平台下（Windows，Mac，Lunix）这个文件所在的路径不一样，
分别如下:

* Windows：`C:\WINDOWS\system32\drivers\etc`
* Mac：`/etc/hosts`
* Linux：`/etc/hosts`

用你熟悉的编辑器打开`hosts`文件，在最下面添加下面两个地址：

```
203.208.46.146 dl.google.com
203.208.46.146 dl-ssl.google.com
```

保存，退出即可。

***

## Android Studio 中文乱码解决方法

很多同学都安装了Android Studio，但是发现中文是乱码，其实这个很好解决的。在IDE里点击`File`，选择`Settings`(快捷键是`Ctrl+alt+s`).
在打开的窗口中，找到`IDE Settings`下的`Appearance`，在右侧勾选上`“Override default fonts by”`，然后在第一个下拉框中选择字体为`“simsun”`，然后apply，重启IDE，就好了。
