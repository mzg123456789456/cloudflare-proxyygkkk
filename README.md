Cloudflare Workers 代理
原项目：https://github.com/yonggekkk/Cloudflare-vless-trojan

高！实在是高！白嫖 nat64 公共网关来做代理，太绝了！以后也用不着搭建什么 proxyip 节点，搭 nat64 网关就行👍

视频教程
https://youtu.be/HQcLxYbPSgo

固定ip，解决 twitch 无法观看 1080p 直播
我在涌哥的脚本基础上，增加了自定义 proxydomains 变量，因此现在可以将需要固定ip访问的网站设置到 proxydomains 变量中，这样就不会跳 ip 了。

变量设置
只需要设置 uuid 就行，如果不担心被其他人扫到，uuid 都不需要改，不过还是建议修改

变量作用	变量名称	变量值要求	变量默认值	变量要求
1、必要的uuid	uuid (小写字母)	符合uuid规定格式	万人骑uuid：86c50e3a-5b87-49dd-bd20-03c7f2735e40	建议
致谢
https://github.com/yonggekkk/Cloudflare-vless-trojan - 原项目仓库
@yonggekkk - 原项目作者
免责声明
本项目仅供学习交流使用，请遵守当地法律法规。
