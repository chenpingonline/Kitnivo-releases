# Kitnivo 插件发布

此仓库仅发布 Kitnivo 插件二进制包和远程更新清单，源码仓库保持私有。

插件包适用于 Apple Silicon（arm64）。截图与长截图要求 macOS 14 及以上，屏幕录制要求 macOS 15 及以上。

在 Kitnivo 的插件管理中点击“更新”，客户端将检查版本并下载、校验和安装新版，保留插件数据与设置。也可下载 ZIP 后解压，通过本地插件更新入口安装 `.bundle`。

官方更新清单：https://github.com/chenpingonline/Kitnivo-releases/releases/latest/download/updates.json

每次 Release 包含插件 ZIP 和 `updates.json`；清单包含插件 ID、版本、CPU 架构、下载地址、字节数及 SHA-256。客户端还会校验插件开发者签名，并在安装失败时回滚。
