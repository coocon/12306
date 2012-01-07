12306 订票助手(谷歌浏览器版)
===========================

请使用谷歌浏览器，该助手暂只负责登录和更新车票

功能
------------

*	自动尝试登录，登录成功提示
*	根据条件自动查票，有票以后声音提示


使用
------------

有使用 12306自动登录 和 12306自动查询 的同学可在 插件管理(chrome://settings/extensions) 里面卸载了，因为功能重复了

使用谷歌浏览器 [点击这里](https://github.com/zzdhidden/12306/raw/master/12306BookingAssistant.user.js), 然后确认安装此userscript

安装成功后 [点击这里](https://dynamic.12306.cn/otsweb/) 开始订票吧

首先输入好登录名，密码，和验证码。 点击自动登录，即可进行多次尝试登录，直至登录成功

![登录](https://github.com/zzdhidden/12306/raw/master/login.jpg)

登录之后到车票预订页面，选择好出发地，目的地，和出发时间，点击开始刷票，就会不断更新火车票，只到有票为止，刷到之后会有通知提示和声音提示

![查询](https://github.com/zzdhidden/12306/raw/master/query.jpg)

那些贡献者们....
------------

*	[Jingqin Lynn](https://gist.github.com/1554666) 自动查票
*	[Kevintop](https://gist.github.com/1570973) 自动登录


问题
--------------------

*	登录的验证码，不去请求那个验证码连接，验证码不会更新，于是可使用ajax请求登录


