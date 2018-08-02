MSTS新平台解决方案
====================
制作：jhcwd@微软模拟火车中国论坛
----------
论坛网址/Our forum：[http://msts.xclub.tw]("http://msts.xclub.tw")

目前由于硬件平台的逐渐更新，导致在新平台上MSTS出现各种各样的兼容性问题。解决方案如下。

With the update of hardware,errors occur in the running of MSTS.This document aims to solve this problem.

## 第一步：检测硬件/Check your hardware
这一步的目的在于检测电脑平台（主要是显卡）是AMD平台还是Nvida平台

The purpose of this step is to check your plaform of your computer(especially the graphics)is based on AMD or Intel. 

需要注意的是，你的计算机可能拥有不只一种显卡!

Notice that your computer may have more than one graphic!

参考软件：鲁大师

###或者通过系统自身的功能查看，方法如下：

>1.右键桌面上的“此电脑”/“计算机”/“我的电脑”图标，并选择“属性”

>2.点击左侧“设备管理器”

>3.点击右侧窗格中的“显示适配器”

>4."HD Graphics""UHD"字样，代表Intel集成显卡

>"HD Graphics" or "UHD" represents for intergrated graphics(Intel)

>"Randeon""ATI"等字样代表AMD显卡

>"randeon""ATI" represents for AMD graphics

>"Nvidia"字样代表Nvidia显卡

>"Nvidia" represents for Nvidia graphics

## 第二步：选择解决方案/Choose the best solution

###对于英特尔（集成）显卡的用户/For Intel (Intergrated) graphics users

>尝试直接运行程序，如果出现显示不正常现象，请尝试将驱动程序更新到最新。若还是不行，则只能使用OR替代MSTS进行游戏

>Try to run MSTS directly.If there's something wrong with the display,try to update your graphics driver to the latest version.If this doesn't work,you have no chioce but to use OR instead of MSTS.

###对于AMD显卡用户/For ATI Graphics users

>请使用补丁修复MSTS，即可完美运行游戏

>Use patches to fix MSTS so that your game can run perfectly.

>补丁下载地址/Download link of patches：

>链接/Link: [https://pan.baidu.com/s/1XTA6hxonA0kwxmjRFJ_frQ]("https://pan.baidu.com/s/1XTA6hxonA0kwxmjRFJ_frQ") 密码/Password: ttam

###对于Nvidia显卡用户/For Nvidia graphics users

>使用独立显卡运行游戏，部分型号显卡可正常运行，但也有部分型号仍然会出现问题。如果有问题那只能使用OR替代MSTS进行游戏。

>Use Nvidia graphics to run the game.Some models can run the games perfectly,while others can not.In the latter case you have no choice but to use OR instead of MSTS.

>在NVIDIA控制面板内可以找到关于对指定程序使用Nvidia显卡运行的选项，参照[https://jingyan.baidu.com/article/6d704a13d39f3028da51ca49.html]("https://jingyan.baidu.com/article/6d704a13d39f3028da51ca49.html")

>You can find the option of using Nvidia graphics to run programs in the NVIDIA control panel.Reference:[https://jingyan.baidu.com/article/6d704a13d39f3028da51ca49.html]("https://jingyan.baidu.com/article/6d704a13d39f3028da51ca49.html")
