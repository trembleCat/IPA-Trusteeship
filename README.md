# IPA托管

#### 介绍
IPA托管

使用浏览器安装ipa程序
  
查看详细使用教程[IPA托管](https://www.jianshu.com/p/08172adacc97)
  
#### 使用说明

1.复制plist文件内容   
   
2.修改图片以及ipa包的url地址 （第14行，第22和30行）
  
3.title是下载提示的标题，下载完成后APP名称依然为项目设置的名称 （第36行） 
   
4.修改id与version使其和app相同  （第37和42行） 
  
5.在plist的url链接前拼接以下代码  
  
itms-services://?action=download-manifest&url=         
  
如 ：itms-services://?action=download-manifest&url=https://raw.githubusercontent.com/trembleCat/IPA-Trusteeship/master/ipa.plist  
  
将上边的链接生成二维码或直接使用Safair浏览器打开即可弹出安装程序界面  
(由于github原因，所以安装速度会很慢，最终将ipa包和plist文件放在自己服务器即可)  

