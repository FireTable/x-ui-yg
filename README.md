本项目基于上游X-UI项目（ https://github.com/vaxilu/x-ui ）进行略微的功能改动！后续将紧跟上游X-UI的版本更新！

具体变化如下

1：集成关闭防火墙及开放iptables所有端口规则的功能，默认启动。

2：集成纯IPV6的VPS自动加入dns64功能，默认启动。

3：集成一键ACME证书申请选项，可选。

4：集成默认每分钟自动检测X-UI与Xray是否运行的进程守护功能，默认启动。

5：删减docker文件，已移除。

一键脚本（支持纯IPV4、纯IPV6、双栈V4V6的VPS）

```
bash <(curl -Ls https://cdn.jsdelivr.net/gh/kkkyg/x-ui-yg@0.3.2.5/install.sh)
```

安装过程会提示上游X-UI项目最新版本号与本项目最新版本号，默认安装本项目
