#whmcs-kami
whmcs适用的简易线下卡密充值页面

关键词：whmcs | page | kami | credit | 卡密 | 充值

##测试环境
Centos7 X86_64 | Apache 2.4.6 | PHP 5.4.16 | WHMCS 6.2.0

##主要功能
预先设定一个或若干个卡密及其对应面额。在其他销售平台上出售卡密，用户在whmcs相关页面输入线下购买的卡密后获得对应whmcs余额。完成卡密充值后即可与其他whmcs余额充值方式一样使用余额进行产品的购买和续费。

ps：以下是原作者QQ 550014614 。我已经忘了是从哪里下载到的这个卡密充值，由于代码不是很完善所以自己修改了一下顺便发到github。

##文件结构
/kami.sql&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;mysql数据库备份文件

/whmcs/kami.php&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;卡密充值主页面

/whmcs/kami_get.php&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;管理员快速添加卡密页

/whmcs/kami_pay.php&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;卡密充值结果返回页

/whmcs/templates/six/kami.tpl&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;卡密充值主tpl

/whmcs/templates/six/kami_fail.tpl&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;卡密充值失败tpl

/whmcs/templates/six/kami_success.tpl&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;卡密充值成功tpl

/whmcs/templates/six/kami_withoutlogin.tpl&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;卡密充值未登录tpl

