# MonkeyDevInMacOS15
安装MonkeyDev可能需要的文件

最近帮同事在新电脑上安装MonkeyDev插件时遇到的问题

在新版系统和新版xcode环境下，MonkeyDev脚本会有一个路径读不到，估计是新旧版这个路径不同

好在自己这里两台电脑，专门把一台电脑停留在了10.14，因为15刚出的时候确实很多东西不兼容

也算是派上了用场，直接在10.14下的老版xcode中把报错信息中的路径和文件夹直接拷贝到新版里就ok了

路径：/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/Library/Xcode/Specifications

有人同样有需求的话自提吧，就是这个项目中这个文件夹，根据报错放进去就好

从10.14一路升上来的不会有问题，目前只发现全新的会出现。
