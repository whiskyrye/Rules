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


# momo推荐使用订阅链接的方式
- 换成支持订阅链接的sing-box内核，替换OpenWrt目录/usr/bin/下sing-box内核文件，reF1nd分支内核下载：https://github.com/reF1nd/sing-box-releases/releases
- reF1nd分支内核电报群：[https://t.me/sing_box_reF1nd](https://t.me/sing_box_reF1nd)
- 软路由下载musl版本即可
- 更换配置文件注意清理缓存，删除/etc/momo/run/cache.db
- [蓝奏网盘下载地址](https://www.ilanzou.com/s/XpIMrLWb)

# sing-box配置文件，版本1.13.x
- momo.json 适配momo，Redir-host，使用reF1nd分支内核
- momo_fakeip.json 适配momo，fakeip，使用reF1nd分支内核
- config.json为裸核版本，配合singbox订阅后端使用
- template-momo为reF1nd分支内核提供的momo配置模版文件，仅供学习

# 客户端
- Windows：GUI.For.SingBox GitHub：[https://github.com/GUI-for-Cores/GUI.for.SingBox](https://github.com/GUI-for-Cores/GUI.for.SingBox)
- Android：sing-box for Android  GitHub：[https://github.com/SagerNet/sing-box](https://github.com/SagerNet/sing-box)
- Apple platforms：[详情](https://sing-box.sagernet.org/clients/apple/)

# sing-box规则集
- MetaCubeX 维护的规则集：https://github.com/MetaCubeX/meta-rules-dat/tree/sing/
- SingBox 官方维护的规则集：https://github.com/SagerNet/sing-geosite/tree/rule-set

# Thanks
momo插件仓库：[https://github.com/nikkinikki-org/OpenWrt-momo](https://github.com/nikkinikki-org/OpenWrt-momo)

sing-box内核仓库：[https://github.com/SagerNet/sing-box](https://github.com/SagerNet/sing-box)    [官方配置实例](https://sing-box.sagernet.org/manual/proxy/client/#virtual-interface)

QCY配置文件：[https://github.com/qichiyuhub/rule/tree/main/config/singbox](https://github.com/qichiyuhub/rule/tree/main/config/singbox)

sing-box订阅后端：[sing-box-subscribe-doraemon.vercel.app](https://sing-box-subscribe-doraemon.vercel.app/)  | [sing-box订阅后端github](https://github.com/Toperlock/sing-box-subscribe)
