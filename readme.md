# nikki、momo插件配置文件
## 自编译的ImmortalWrt下载（包含momo、nikki插件）：https://github.com/whiskyrye/ImmortalWrt-Actions/releases
# mihomo、nikki配置
- fakeip表示DNS模式为FakeIP模式
- 其余为Redir-host模式
- mihome与nikki区别在于规则引用不同,nikki只能用于openwrt-nikki插件，mihomo在nikki及其他客户端中都可使用
# mihomo、nikki规则集
- [rules-dat for mihomo](https://github.com/MetaCubeX/meta-rules-dat)
- [mihomo：meta branch](https://github.com/MetaCubeX/meta-rules-dat/tree/meta)
# icon图标仓库
- [Icons for Dashboard, MetacubeX, Zashboard](https://github.com/Vbaethon/HOMOMIX)


## ImmortalWrt需要特别注意的事情
如果有问题，请自行关闭网络 -> DHCP/DNS -> DNS 重定向这一选项，否则会导致DNS污染/分流错误的的情况发生。

## Thanks
- [OpenWrt-nikki](https://github.com/nikkinikki-org/OpenWrt-nikki)
- [OpenWrt-momo](https://github.com/nikkinikki-org/OpenWrt-momo)
