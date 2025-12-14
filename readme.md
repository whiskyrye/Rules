## nikki、momo插件配置文件
# 自编译的ImmortalWrt下载（包含momo、nikki插件）：https://github.com/whiskyrye/ImmortalWrt-Actions/releases
- fakeipfilter：用于自定义直连域名不走fake-ip
- mydirect：自定义直连域名
- myproxy：自定义代理域名
- myblock：自定义屏蔽域名

## ImmortalWrt需要特别注意的事情
如果有问题，请自行关闭网络 -> DHCP/DNS -> DNS 重定向这一选项，否则会导致DNS污染/分流错误的的情况发生。
