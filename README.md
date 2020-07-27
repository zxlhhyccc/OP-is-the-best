![](https://pic.downk.cc/item/5f13d9fc14195aa594c0dc50.png)              

* [墙外小报](https://t.me/FQnews)        
* telegram汉化：[汉化](https://t.me/setlanguage/classic-zh)         
* 有恩山论坛账号的大哥哥们回复帖子任意内容顶一下热度即可谢谢❤️：[帖子](https://www.right.com.cn/forum/thread-4041413-1-1.html)                   
* IT界第一定理：遇到问题先重启试试                   

# OpenWRT固件               
* [x86_64 ssrpOpenWRT软路由固件频道](https://t.me/ssrpOpenWRT)           
👆主ssrp插件（[功能截图](./ssrp/leanbuild.md)）。推荐小白及不爱折腾用户使用            
  ** [ssrp避免节点乱跳](./ssrp/qiehuan.md)            
* [ssrpIPK爱好者频道](https://t.me/ssrpIPKnb)                         
👆luci-app-ssr-plus_XXX-X_all.ipk            
* [Lean@全体成员频道](https://t.me/LeanAtYou)               
👆主ssrp插件。Lean艾特你，发布各种Lean原味硬路由/ARM软路由固件、windows镜像、Lean通知......                       

----------------------------------------------------------------------------------
* [x86_64 passwallOpenWRT软路由固件频道](https://t.me/passwallOpenWRT233)          
👆主passwall插件（[功能截图](./passwall/lienolactions.md)）。推荐喜爱自定义更多用户使用                 
  ** [passwall按地址分流](./passwall/fenliu.md)                 
  ** [passwall按设备分流](https://youtu.be/qkga9DN5H08)         
  ** [passwall的守护进程/翻墙测速/避免BT走代理](./passwall/ShouhuZhuanfa.md)                    
  ** [passwall另一种故障切换方法/重置passwall单一插件/隐藏和显示passwall插件](./passwall/QiehuanChongzhiYincang.md)                          
  ** [passwall的负载均衡使用](https://youtu.be/TRdOfTykgRw)          
  ** [passwall+smartdns](https://youtu.be/vqAeeLbqvOs)         
* [passwallIPK爱好者频道](https://t.me/passwallIPKnb)                  
👆luci-app-passwall_XXX-X_all.ipk                 

---------------------------------------------------------------------------------- 
* [x86_64 clashOpenWRT软路由固件频道](https://t.me/clashOpenWRT233)                 
👆主openclash插件。推荐动手能力超强喜爱究极自定义的专业用户使用                                  
  ** [三分钟上手](https://youtu.be/6qqWEPK9ODs)             
  ** [搭配使用smartdns&openclash](https://youtu.be/xb-b2xS-tqw)                
  
----------------------------------------------------------------------------------
* [N1 passwallOpenWRT固件频道](https://t.me/n1passwall)                  
👆N1盒子也可跑passwall，功耗性能出色           

----------------------------------------------------------------------------------
///其他的硬路由/ARM软路由的OpenWRT固件可在恩山论坛搜索下载到热心站友编译分享的固件：[恩山论坛](https://www.right.com.cn/forum/forum-72-1.html)             
///集成越少插件的固件越低概率出bug ——Lean                     

# 相关工具            
* [PE下IMG写入硬盘软件](https://github.com/OPisthebest/OP-is-the-best/releases/tag/DiskImg.exe1.2)       
* [IMG写入TF卡软件](https://github.com/balena-io/etcher/releases)         
* [IMG转VMDK](https://github.com/OPisthebest/OP-is-the-best/releases/tag/StarWindConverter)            
* [微PE启动盘](http://www.wepe.com.cn/download.html)           
* [网络测速](https://www.speedtest.net/)               
* [查看自己IP地址](https://ip.skk.moe/)               
* [ping测你的IP的连通性](http://ping.pe/)                         

# 升级新版本/切换版本/回滚/重置固件教程               
* [web页面上传升级/重置/切换/回滚](./upgrade.md)               

# 全新刷固件教程                 
* [PE下写盘刷机](https://youtu.be/50kjIPu3kDY)           
* [创建接口(如果缺少WAN口之类的你需要的)](./newinterface.md)                      

///注意：写盘工具一定要下本博客#相关工具“PE下IMG写入硬盘软件”的版本，大大降低报错概率               
///固件自然也推荐用本博客上方给出的发布频道里的几乎都是插件作者亲自编译的官方固件啦        
 
# 常用插件的使用教程                  
* [如何DDNS外网无需加端口远程访问 dynuDNS解析 URL转发](https://youtu.be/c4HSZzTM7G0)                   
* [ZeroTier 免费虚拟局域网教程：内网穿透 OpenWrt、群晖NAS](https://youtu.be/U3aRXg3ejks)            
* [旁路由下访问国内网络缓慢/失败解决办法](./sidefirewall.md)              

# OpenWRT本土化Fork                
* [Lean的开发Fork](https://github.com/coolsnowwolf/lede)             
* [Lean的稳定Fork](https://github.com/coolsnowwolf/openwrt)            
  ** [Lean授权的actions](https://github.com/KFERMercer/OpenWrt)                  

///目前最主流的Fork，内置Lean开发的ssrp（ShadowsocksR Plus+)翻墙插件，除了x86/ARM，也为一些廉价硬路由赋予了翻墙的价值         
///近期发现没了ssrp的请看[这里](https://github.com/coolsnowwolf/lede/blob/master/feeds.conf.default)(去掉#注释即可)                  

------------------------------------------------------------------------------------------------------------------
* [Lienol的Fork](https://github.com/Lienol/openwrt)            
  ** [Lienol的actions](https://github.com/Lienol/openwrt-actions)                        

///紧跟官方OpenWRT，Lienol只关注x86设备，内置Lienol开发的passwall翻墙插件，有一些Lienol改的LuCI主题较为美观           

----------------------------------------------------------------------------------------------------------------------------
* openclash开发者vernesong没有DIY自己的OpenWRT，他的openclash项目地址：[openclash](https://github.com/vernesong/OpenClash)                 

# 相关命令/位置            
* 完全删除lede文件           
rm -rf lede                 
* 清空回收站          
sudo rm -rf ~/.local/share/Trash/*                           
* Windows的HOSTS文件位置(当出现一些网页元素加载失败时可以尝试清空HOSTS规则)                       
C:\Windows\System32\drivers\etc                       
* powershell中SSH连接路由器后台举例               
ssh root@192.168.2.1             
password        
* openwrt恢复出厂设置命令             
firstboot      
* 修改后台密码命令          
passwd       
* 修改LAN口IP         
vi /etc/config/network
* 远古版本ssrp芝麻开门命令            
echo 0xDEADBEEF > /etc/config/google_fu_mode                 

# 友链              
* Lean的         
  [OP编译官方大群](https://t.me/joinchat/JhKgAA6Hx1uiihA7RaTW1w)                
  [OP编译官方频道](https://t.me/opbypd)      
  QQ群：297253733                        
* Lienol的                  
  [OpenWRT吹水群](https://t.me/openwrtcs)              
* [IT奶爸](https://www.youtube.com/c/IT%E5%A5%B6%E7%88%B8/videos)         
* [BIGDONGDONG](https://www.youtube.com/c/BIGdongdong/videos)            
* [恩山论坛](https://www.right.com.cn/forum/forum-72-1.html)             
* [奈菲影视](https://www.nfmovies.com/)        
* [沁沁的上网笔记](https://quickvideosharing.github.io/note/)                

# 优质翻墙机场(您的支持是我持续更新的动力❤)               
* [管理员本本监督合作机场](./AIRPORT.md)                














