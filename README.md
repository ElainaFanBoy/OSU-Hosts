由于在中国大陆境内大部分Cloudflare的IP地址访问速度极慢，所以在游玩使用此CDN的游戏OSU!体验并不好。


请用管理员权限，用任何一个文本编辑器（例如记事本）打开位于X:\Windows\System32\drivers\etc(X代表你的系统盘符，一般是C盘)下的hosts（没有后缀名）文件。


在hosts的底部添加本仓库hosts文件内的全部内容。保存后运行本仓库cf_hosts文件（Windows系统使用.bat后缀的）。


第一次运行时，控制台会提示输入IP地址，只须输入233.33.33.33即可，后续可以一劳永逸。等待完成即可。


如果下载速度无法测试，请阅读一下项目的Readme：
https://github.com/XIU2/CloudflareSpeedTest


或者这个issue：https://github.com/XIU2/CloudflareSpeedTest/issues/168


除了移动用户外，其余的用户的最低延迟也要100ms以上。所以如果你不是移动用户，却发现了有低于100ms的IP，请参照这个issue：https://github.com/XIU2/CloudflareSpeedTest/issues/111
