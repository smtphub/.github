# SMTPHub 项目介绍

SMTPHub 是一款基于 PHP 语言开发的 SMTP 服务管理和邮件发送系统，类似于邮件推送 API 服务，可实现同一个 SMTP 接口对接多个业务站点，多个业务站点可以统一调用本系统接口实现邮件发送。

支持多个 SMTP 的管理，通过接口 AppSecret 的验证防止非法使用，自动记录每一个邮件发送内容以便审查。帮助企业实现所有站点、app 等产品发送邮件的统一调用和规范管理。

将 SMTP 的调用集中在同一个系统可以防止触发 SMTP 异地登录事件，避免第三方邮箱提供方检测到异常登录可能导致的发送失败的问题。

在线演示：[http://smtphub.usite.pub/admin](http://smtphub.usite.pub/admin)

账号：admin/123456
