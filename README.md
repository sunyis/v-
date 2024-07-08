
V免签  —— 个人开发者收款解决方案
===============

> V免签仅供个人开发者调试测试使用，请勿用于非法用途，商用请您申请官方商户接口


## 版本说明
	1.去除登录提示弹窗
	2.修改php版本导致登录出错


## 安装
 + 推荐使用宝塔面板安装，以下教程为宝塔面板安装教程
 + 环境参考:
    + PHP-7.4
    + Nginx 1.71.10
    +  MySQL 5.6.50
        

    1、下载源代码,Clone or download->Download ZIP
    
    2、宝塔面板中新建网站，设置：
        
        + 网站目录->运行目录 设置为public并保存
        + 伪静态 设置为thinkphp并保存
        + 默认文档 设置将index.html放在第一行并保存
    
    3、打开网站目录 config/database.php ，设置好您的mysql账号密码。
    
    4、导入数据库文件（位于根目录）vmq.sql到您的数据库。
    
    5、至此网站搭建完毕，请访问后自行修改配置信息！默认后台账号和密码均为admin


## 监控端
+ 在项目根目录放置了Android.apk 安装即可
 
安装
推荐使用宝塔面板安装，以下教程为宝塔面板安装教程，其他环境请参考自行配置

1、下载源代码,Clone or download->Download ZIP

2、宝塔面板中新建网站，设置：

 + 网站目录->运行目录 设置为public并保存
 + 伪静态 设置为thinkphp并保存
 + 默认文档 设置将index.html放在第一行并保存
3、打开网站目录 config/database.php ，设置好您的mysql账号密码。

4、导入数据库文件（位于根目录）vmq.sql到您的数据库。

5、至此网站搭建完毕，请访问后自行修改配置信息！默认后台账号和密码均为admin

升级说明：请您直接下载新版本覆盖旧版本即可！

调用
请部署完成后访问后台，有详细的Api说明
注意
本系统原理为监控收款后手机的通知栏推送消息，所以请保持微信/支付宝/V免签监控端后台正常运行，且添加到内存清理白名单！

v免签面向用户是个人开发者，如果您不懂如何开发网站，那么v免签不适合您的使用！

v免签的原理是监控手机收到收款后的通知栏推送信息，所以不适合于商用多用户的情况，如果您想用于商用，请二次开发！

v免签是免费开源产品，所有程序均开放源代码，所以不会有收费计划，因此作者不可能教会每个人部署安装，请参考文档多百度谷歌，v免签使用具有一定的技术门槛，请见谅！

v免签的监控端并不适配所有手机，遇到手机无法正常使用的时候，请您更换手机或使用模拟器挂机！

v免签拥有双语言服务端，当您使用php版本服务端遇到问题的时候，请您尝试使用java版本服务端，php版本服务端配置略复杂，需要配置伪静态规则，请知悉！

正常的安装步骤简略如下

下载服务端部署(GitHub中下载的为最新版)
登录网站后台更改系统设置
打开网站后台监控端设置
下载监控端
安装监控端后使用手动配置或扫码配置
监控端中点击开启服务跳转到辅助功能中开启服务
开启服务后返回v免签点击检测监听权限
如果显示监听权限正常，至此安装完毕，如果只收到通知栏推送的测试通知，则系统不兼容无法正常监听
如果显示监听权限正常，还是无法正常运行，那么请确定微信是否关注 “微信支付” 和 “微信收款助手” 这两个公众号
手机设置步骤（教程为MIUI系统，非MIUI系统请参考教程进行设置）

关闭系统神隐模式

（旧版MIUI系统）在系统【设置】 - 【其他高级设置】 - 【电量与性能】 - 【神隐模式】 - 【V免签监控端】设置为关闭

（新版MIUI系统）在系统【设置】 - 【其他高级设置】 - 【电量与性能】 - 【省电优化】 - 【应用智能省电】，将V免签监控端、微信、支付宝的3个APP全都改为无限制

添加内存清理白名单

关闭WIFI优化

（旧版MIUI系统）在系统【设置】 - 【WLAN】 -【高级设置】 -【WLAN优化】，关闭它。

（新版MIUI系统）在系统【设置】 - 【WLAN】 -【高级设置】 - 【在休眠状态下保持WLAN网络连接】改为“始终”

开启推送通知

系统【设置】 - 【通知和状态栏】 - 【通知管理】中，找到这3个App，把里面的开关全部打开

在微信的【设置】 - 【勿扰模式】中，关闭勿扰模式

在微信的公众号，关注 【微信收款助手】 这个公众号

在支付宝的主页，上方搜索框 搜索 【支付助手】 ，进入支付助手，右上角小齿轮，打开【接收付款消息提醒】

v免签支持的通知有：

支付宝个人收款的推送通知
支付宝商家二维码的收款推送通知
支付宝店员通绑定的店员账号收款的推送通知
微信二维码收款推送通知
微信店员收款推送通知 


## 版权信息

V免签遵循 MIT License 开源协议发布，并提供免费使用，请勿用于非法用途。




