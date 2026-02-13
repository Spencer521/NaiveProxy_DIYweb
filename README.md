# NaiveProxy_DIYweb

NaiveProxy

https://github.com/klzgrad/forwardproxy/releases
https://bulianglin.com/archives/naive.html

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
