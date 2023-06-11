------------------------------
forked from keke1023/Padavan.
仅供自己学习测试之用。
------------------------------

# Padavan
基于hanwckf,chongshengB以及padavanonly的源码整合而来，支持kvr。编译方法同其他Padavan源码，主要特点如下：  
1.采用padavanonly源码的5.0.4.0无线驱动，支持kvr。
2.添加了chongshengB源码的所有插件。
3.其他部分等同于hanwckf的源码，有少量优化来自immortalwrt的padavan源码。
4.添加了MSG1500的7615版本config。
以下附上他们四位的源码地址供参考  
https://github.com/hanwckf/rt-n56u  
https://github.com/chongshengB/rt-n56u  
https://github.com/padavanonly/rt-n56u  
https://github.com/immortalwrt/padavan  

# 使用备忘
1.固件默认设置： wifi名称Finer2023及Finer2023_5G，wifi密码：自用不公开；  管理地址192.168.10.1，管理账号caomusan密码均：自用不公开。  
2.常用文件目录： 版本信息trunk/versions.inc；机型文件trunk/configs/templates； 固件默认配置信息trunk/user/shared/defaults.h； 管理页面页脚信息trunk/user/www/Makefile；  图标文件夹trunk/user/www/n56u_ribbon_fixed/bootstrap/img；
3.小米路由器R3Gv2版本配置与小米R4A（旧版）一致，固件可以通用。
