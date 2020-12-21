# 小程序·云开发静态网站托管跳转小程序示例

非个人主体的认证的小程序，使用静态网站托管的网页，可以免鉴权跳转任意合法合规的小程序。

静态网站网页在微信客户端打开时，wx.config 可以传入小程序 AppID 并且不需计算签名，也就是免鉴权即可使用跳转小程序的能力。

关于[微信文档](https://developers.weixin.qq.com/miniprogram/dev/wxcloud/guide/staticstorage/jump-miniprogram.html)