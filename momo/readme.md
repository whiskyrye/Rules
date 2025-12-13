# momo推荐使用订阅链接的方式
- 替换支持订阅链接的sing-box内核，替换OpenWrt目录/usr/bin/下sing-box内核文件，reF1nd分支内核（电报频道内下载）：[https://t.me/sing_box_reF1nd](https://t.me/sing_box_reF1nd)
- 更换配置文件注意清理缓存，删除/etc/momo/run/cache.db

# sing-box配置文件，版本1.12.x
- momo.json 适配momo，Redir-host，支持订阅
- momo_fakeip.json 适配momo，fakeip，支持订阅
- config.json为裸核版本，配合singbox订阅后端使用
- template-momo为reF1nd分支内核提供的momo配置模版文件

# sing-box订阅后端搭建与使用
订阅后端仓库地址：[https://github.com/Toperlock/sing-box-subscribe](https://github.com/Toperlock/sing-box-subscribe)
- docker搭建命令：Docker-容器-新增-命令行-粘贴以下命令-提交
```
docker run -d \
  --name sing-box \
  -p 5000:5000 \
  --restart always \
  dockerhub16/sing-box-subscribe:latest
```
订阅地址组合：http://192.168.2.1:5000/config/机场订阅&file=配置文件地址

- 机场订阅为clash或者通用订阅即可，多个机场用 | 符合分割，最多可放3个，配置文件使用config.json，配置文件地址为源码raw地址。

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
