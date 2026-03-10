# NaiveProxy_DIYweb

NaiveProxy
参考
https://github.com/crazypeace/naive
编译好的插件
https://github.com/klzgrad/forwardproxy/releases
不良林视频文档
https://bulianglin.com/archives/naive.html


编译
apt install golang-go

Go installation¶:https://go.dev/doc/install

go install github.com/caddyserver/xcaddy/cmd/xcaddy@latest

~/go/bin/xcaddy build --with github.com/caddyserver/forwardproxy=github.com/klzgrad/forwardproxy@naive

> [!NOTE]
>
>caddy常用指令：
>
>- **前台运行caddy：**  ./caddy run
>- **后台运行caddy：** ./caddy start
>- **停止caddy：** ./caddy stop
>- **重载配置：** ./caddy reload>
>- **检查语法**       ./caddy validate

caddy配置守护进程（开机自启）：https://github.com/klzgrad/naiveproxy/wiki/Run-Caddy-as-a-daemon


https://caddyserver.com/docs/caddyfile/options#general-options

默认证书路径

/root/.local/share/caddy/certificates/acme-v02.api.letsencrypt.org-directory/42782.xyz/42782.xyz.key
