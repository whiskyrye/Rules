# singbox配置文件，版本1.12.x
- config.json为裸核版本及专用后端
- zijian-momofake.json为自建节点，入站匹配momo、fakeip模式
- momo.json为入站匹配momo及专用后端
- momofake.json为入站匹配momo及专用后端、fakeip模式
- sub-momofake.json为适配sub-store订阅、入站匹配momo、fakeip模式
- fork-momofake.json为适配fork内核、入站匹配momo、fakeip模式

# fork分支内核下载（电报频道内下载）：
[https://t.me/sing_box_reF1nd](https://t.me/sing_box_reF1nd)

下载后替换openwrt中singbox内核（/usr/bin/,注意清理缓存/etc/momo/run/cache.db）,支持订阅及订阅更新

# Thanks
momo插件仓库：[https://github.com/nikkinikki-org/OpenWrt-momo](https://github.com/nikkinikki-org/OpenWrt-momo)

singbox内核仓库：[https://github.com/SagerNet/sing-box](https://github.com/SagerNet/sing-box)    [官方配置实例](https://sing-box.sagernet.org/manual/proxy/client/#virtual-interface)

QCY配置文件：[https://github.com/qichiyuhub/rule/tree/main/config/singbox](https://github.com/qichiyuhub/rule/tree/main/config/singbox)

sing-box 基础教程:[https://icloudnative.io/posts/sing-box-tutorial/](https://icloudnative.io/posts/sing-box-tutorial/#%E5%85%A5%E7%AB%99%E9%85%8D%E7%BD%AE)

sing-box配置生成：[sing-box-subscribe-doraemon.vercel.app](https://sing-box-subscribe-doraemon.vercel.app/)  | [github源码](https://github.com/Toperlock/sing-box-subscribe)
