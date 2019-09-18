# IPA托管测试

#### 介绍
IPA托管测试

测试浏览器安装ipa程序

#### 使用说明

1.复制plist文件内容  
2.修改图片以及ipa包的url地址  
3.修改id与version使其和app相同  
4.在plist的url链接前拼接以下代码  
itms-services://?action=download-manifest&url=         
  
如 ：itms-services://?action=download-manifest&url=https://gitee.com/kevincool/ipaTest/raw/master/ipa_plist  
  
将上边的链接生成二维码或直接使用Safair浏览器打开即可弹出安装程序界面  

