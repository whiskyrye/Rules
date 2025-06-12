## mihomo/nikki yaml 配置文件
### ImmortalWrt需要特别注意的事情
请自行关闭网络 -> DHCP/DNS -> DNS 重定向这一选项，否则会导致DNS污染/分流错误的的情况发生。

[rules-dat for mihomo](https://github.com/MetaCubeX/meta-rules-dat)➡[mihomo：meta branch](https://github.com/MetaCubeX/meta-rules-dat/tree/meta)

### config-nikki 用于软路由
1. 规则使用geosite、geoip，规则较多可删减
2. lite是精简，自用
### config-mihomo 用于手机、电脑客户端
1. 规则使用rule-set，规则较多可删减
2. lite是精简，自用
### fakeipfilter
用于自定义直连域名不走fake-ip
### mydirect
自定义直连域名
### myproxy
自定义代理域名
