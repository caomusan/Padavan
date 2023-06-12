# Padavan 
参考源码地址：   
https://github.com/keke1023/Padavan/    （主要引用）  
https://github.com/hanwckf/rt-n56u      （参考）  
https://github.com/chongshengB/rt-n56u  （参考）  
https://github.com/a0575/padavan （精简）   
https://github.com/yuos-bit/Padavan （页脚）

# 使用备忘
1.固件默认设置：wifi名称"Finer_%s"及"Finer5G_%s"，密码自用；管理地址192.168.10.1，管理账号caomusan密码自用。  
2.常用文件目录：   
(1)版本信息trunk/versions.inc；机型文件trunk/configs/（boards为配置文件夹，templates为Config文件）；    
(2)固件默认配置信息trunk/user/shared/defaults.h； 管理页面页脚信息trunk/user/www/Makefile；   
(3)图标文件夹trunk/user/www/n56u_ribbon_fixed/bootstrap/img（asus_logo.png为logo）；   
(4)背景设置trunk/user/www/n56u_ribbon_fixed/bootstrap/css/main.css；中文适配信息trunk/user/www/dict/CN.dict；   
(5)默认信息修改trunk/user/shared/defaults.h。其中#define DEF_WLAN_2G_CC与DEF_WLAN_5G_CC必须慎重修改。选择"GB"会适合新旧机器网卡；选择“US”新机器设备网速更快；选择“CN”貌似速度最慢。我选择GB。   
3.小米路由器R3Gv2版本配置与小米R4A（旧版）一致，固件可以通用。
