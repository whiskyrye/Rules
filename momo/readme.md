# momo推荐使用订阅链接的方式
- 替换支持订阅链接的sing-box内核，替换OpenWrt目录/usr/bin/下sing-box内核文件，reF1nd分支内核（电报频道内下载）：[https://t.me/sing_box_reF1nd](https://t.me/sing_box_reF1nd)
- 更换配置文件注意清理缓存，删除/etc/momo/run/cache.db

# singbox配置文件，版本1.12.x
- momo.json 适配momo，非fakeip，支持订阅
- momo_fakeip.json 适配momo，fakeip，支持订阅
- config.json为裸核版本及专用后端
- template-momo为reF1nd分支内核提供的momo配置模版文件

- zijian-momofake.json为自建节点，入站匹配momo、fakeip模式
- momo.json为入站匹配momo及专用后端
- momofake.json为入站匹配momo及专用后端、fakeip模式
- sub-momofake.json为适配sub-store订阅、入站匹配momo、fakeip模式
- fork-momofake.json为适配fork内核、入站匹配momo、fakeip模式


# 客户端
- Windows：GUI.For.SingBox GitHub：[https://github.com/GUI-for-Cores/GUI.for.SingBox](https://github.com/GUI-for-Cores/GUI.for.SingBox)
- Android：sing-box for Android  GitHub：[https://github.com/SagerNet/sing-box](https://github.com/SagerNet/sing-box)
- Apple platforms：[详情](https://sing-box.sagernet.org/clients/apple/)

# Thanks
momo插件仓库：[https://github.com/nikkinikki-org/OpenWrt-momo](https://github.com/nikkinikki-org/OpenWrt-momo)

singbox内核仓库：[https://github.com/SagerNet/sing-box](https://github.com/SagerNet/sing-box)    [官方配置实例](https://sing-box.sagernet.org/manual/proxy/client/#virtual-interface)

QCY配置文件：[https://github.com/qichiyuhub/rule/tree/main/config/singbox](https://github.com/qichiyuhub/rule/tree/main/config/singbox)

sing-box配置生成：[sing-box-subscribe-doraemon.vercel.app](https://sing-box-subscribe-doraemon.vercel.app/)  | [github源码](https://github.com/Toperlock/sing-box-subscribe)
