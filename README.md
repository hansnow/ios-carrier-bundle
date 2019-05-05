# iOS运营商配置文件备份

### 文件说明

+ `version.xml`: 官网下载的运营商配置文件列表，来自于[这个网址](http://ax.phobos.apple.com.edgesuite.net/WebObjects/MZStore.woa/wa/com.apple.jingle.appserver.client.MZITunesClientCheck/version)
+ `<version>-CMCC_cn_iPhone.ipcc`: 对应版本的运营商配置文件

### Tips

+ 刷入老版本配置文件会让系统恢复到自带的运营商配置
+ macOS下打开iTunes的`carrier-testing`模式的命令为
    `defaults write com.apple.iTunes carrier-testing -bool YES`

### 参考资料

+ [如何在苹果官网提取IPCC文件](https://www.feng.com/iPhone/news/2017-03-21/Feng-friends-sharing-how-to-apple-s-official-website-to-extract-the-IPCC-documents_673225.shtml)
+ [使用iTunes刷入IPCC文件](https://bbs.feng.com/forum.php?mod=viewthread&tid=12021334)
+ [Carrier Bundle](https://www.theiphonewiki.com/wiki/Carrier_Bundle)
+ [iTunes Modes](https://www.theiphonewiki.com/wiki/ITunes_Modes)