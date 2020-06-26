【OpenWRT简介】:         
* 2002年底Linksys公司推出WRT-54G，一款基于MIPS架构的无线路由器，使用802.11g标准使得带宽在理论上能够达到54M，在当时是一次巨大的进步。WRT-54G操作系统以Linux取代vXworks，哥伦比亚大学法学院教授Eben Moglen向Linksys提出开源要求。2003年7月，Linksys迫于压力，开源了WRT54G的firmware，不久sveasoft公司开发了Alchemy。从此无线路由器进入了可以刷机的时代。2004年1月出现所谓的OpenWRT，第一个版本是基于Linksys源码及uclibc中的buildroot项目。2005年初，BrainSlayer发布了一个新的发行版：DD-WRT。接着又有HyperWRT。2005年初，OpenWRT开发小组释出第一个 “experimental” 版本，这版本跟Linksys的GPL源码已大相径庭，使用Linux核心源码2.4.3x，还使用了更模块化的buildroot2。2005年以后有White Russian版本。2011年9月21日，juhosg接手OpenWrt，并释出了wr703n的官方源码。2013年4月，发布OpenWrt 12.09，Linux核心版号为3.3版。由于WRT54G价格低廉，OpenWrt又开源免费，成为学习嵌入式Linux最佳平台。OpenWrt本身未带任何UI，需要通过LuCI，webif等各种延伸界面，LuCI界面是使用率最高的Web管理界面。          
* [完整原文](https://zh.wikipedia.org/wiki/OpenWrt)                  

【OpenWRT本土化Fork(可供你自行编译)】：                
* [Lean的Fork](https://github.com/coolsnowwolf/lede)            
目前最主流的Fork，内置Lean开发的ssrp（ShadowsocksR Plus+)翻墙插件，除了x86/ARM，也为一些廉价硬路由赋予了翻墙的价值，可以说是一己之力拉低了可翻墙硬路由的价格门槛，简化的编译依赖自动勾选也让OpenWRT编译门槛降低          
近期发现没了ssrp的请看[这里](https://github.com/coolsnowwolf/lede/blob/master/feeds.conf.default)          
* [Lienol的Fork](https://github.com/Lienol/openwrt)              
紧跟官方OpenWRT，Lienol只关注x86设备，内置Lienol开发的passwall翻墙插件，有一些Lienol改的LuCI主题较为美观                 
目前passwall已经闭源，何时会不会再开源未知                 
* [官方OpenWRT](https://github.com/openwrt/openwrt)          
无翻墙插件，可自行植入翻墙插件                            

【OpenWRT固件(已经编译好的可翻墙固件)】：            
* [x86_64 passwallOpenWRT软路由固件频道](https://t.me/passwallOpenWRT233)         
* [x86_64 clashOpenWRT软路由固件频道](https://t.me/clashOpenWRT233)        
* [x86_64 ssrpOpenWRT软路由固件频道](https://t.me/ssrpOpenWRT)          

【相关工具合集】：         
* [工具](https://opisthebest.github.io/tool/)                         

【友链】：                 
* [沁沁的上网笔记](https://quickvideosharing.github.io/note/)               










