# 自编译的ImmortalWrt下载（包含momo、nikki插件）：https://github.com/whiskyrye/ImmortalWrt-Actions/releases

## ImmortalWrt需要特别注意的事情
如果有问题，请自行关闭网络 -> DHCP/DNS -> DNS 重定向这一选项，否则会导致DNS污染/分流错误的的情况发生。

# 配置文件
- mihomo.yaml：Redir-host模式
- nikki.yaml：Redir-host模式
- momo.yaml：Redir-host模式，使用reF1nd分支内核，sing-box 1.15.x

# momo推荐使用订阅链接的方式
- 换成支持订阅链接的sing-box内核，替换OpenWrt目录/usr/bin/下sing-box内核文件，reF1nd分支内核下载：https://github.com/reF1nd/sing-box-releases/releases
- reF1nd分支内核电报群：[https://t.me/sing_box_reF1nd](https://t.me/sing_box_reF1nd)
- 软路由下载musl版本即可
- 更换配置文件注意清理缓存，删除/etc/momo/run/cache.db
- [蓝奏网盘下载地址](https://www.ilanzou.com/s/XpIMrLWb)

# mihomo、nikki规则集
- [rules-dat for mihomo](https://github.com/MetaCubeX/meta-rules-dat)
- [mihomo：meta branch](https://github.com/MetaCubeX/meta-rules-dat/tree/meta)

# sing-box规则集
- MetaCubeX 维护的规则集：https://github.com/MetaCubeX/meta-rules-dat/tree/sing/
- SingBox 官方维护的规则集：https://github.com/SagerNet/sing-geosite/tree/rule-set


# sing-box客户端
- Windows：GUI.For.SingBox GitHub：[https://github.com/GUI-for-Cores/GUI.for.SingBox](https://github.com/GUI-for-Cores/GUI.for.SingBox)
- Android：sing-box for Android  GitHub：[https://github.com/SagerNet/sing-box](https://github.com/SagerNet/sing-box)
- Apple platforms：[详情](https://sing-box.sagernet.org/clients/apple/)

# icon图标仓库
- [Icons for Dashboard, MetacubeX, Zashboard](https://github.com/Vbaethon/HOMOMIX)

# Thanks
- [OpenWrt-nikki](https://github.com/nikkinikki-org/OpenWrt-nikki)
- [OpenWrt-momo](https://github.com/nikkinikki-org/OpenWrt-momo)
- [sing-box内核仓库](https://github.com/SagerNet/sing-box)
- [sing-box官方配指导](https://sing-box.sagernet.org/manual/proxy/client/#virtual-interface)
