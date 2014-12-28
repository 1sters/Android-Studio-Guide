# Android Studio 常用设置


## 中文乱码

在打开的窗口中，找到IDE Settings下的Appearance，在右侧勾选上“Override default fonts by”，然后在第一个下拉框中选择字体为“simsun”，然后apply，重启IDE，就好了。


## 设置快捷键

依然是在打开的`settings`窗口中，找到`IDE Settings`下的keymap，右侧打开的就是快捷键了，右键单击要修改的快捷键，会弹出一个菜单，选择`“Add keyboard shortcut”`就可以修改快捷键了。删除的话，在弹出的菜单中选择`remove XXX`就行了

## 修改主题

找到`IDE Settings`下的`Appearance`，右侧的`Theme`选择自己喜欢的主体就好了，个人比较喜欢Darcula这个主题。

## 修改字体大小

首先点这个设置按钮，找到 Editor-colors&font-font，默认的不让修改 所以先点击save as  随便点个名字，然后 size就可以修改了，其它颜色什么的也类似....

## 导入Eclipse工程

选择`File`->`Import Project`，在弹出的菜单中选择要导入的工程就好了，选择好以后就直接`next`，在第二个窗口中也选择默认的第一个选项就可以。
需要注意的是，在Android Studio中，有两种工程，一个是`Project`，一个是`Module`，其中Project相当于Eclipse的workspace，Module相当于Eclipse的project

## 导入jar

选择`File`->`Projcet Structure`，在弹出的窗口中左侧找到`Libraries`并选中，然后点击`“+”`，并选择Java就能导入Jar包了

## 删除项目

好吧，这个东西貌似用到的人比较多，其实很简单，Android Studio把删除叫做“Remove”。。。。菜单中显示“Remove XXX”，就是删除的选项

## 修改工程目录

在创建项目的时候，在Project Location中选好工程目录后，要自己输入一个文件夹的名字用来保存工程（至少我第一次使用自己的工程目录时，是这么做的），然后就能使用自己的工程目录了。