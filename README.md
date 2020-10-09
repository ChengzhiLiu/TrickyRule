# TrickyRule
* TrickyRule——针对Google FCM、部分国外域名优化，并且改变路由规则以尝试绕过一些网站和应用的代理工具检测。
* 基于 https://github.com/ACL4SSR/ACL4SSR 及 https://github.com/shadowsocks/shadowsocks-android/blob/master/core/src/main/assets/acl 修改。
* 中国大陆IP库由 https://github.com/17mon/china_ip_list 提供。
* ACL匹配顺序（面向SSR Android类）：[outbound_block_list] >> [proxy_list] >> [bypass_list]；域名 >> IPv4 >> IPv6。
