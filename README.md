# 桌面发射台

接上 Mac 的扩展屏，火箭会从原屏点火，在新屏上入轨。也可以从菜单栏添加要监听的 App，把短时间内打开的一批 App 合为一次发射。

[官网与有声试射](https://harnessloom.com/desktop-launch/) · [下载 macOS DMG](https://github.com/jokeuncle/desktop-launch/releases/download/v1.1.0/DesktopLaunch-1.1.0.dmg) · [发布记录](https://github.com/jokeuncle/desktop-launch/releases)

## 从 GitHub CLI 下载

```sh
gh release download v1.1.0 --repo jokeuncle/desktop-launch --pattern 'DesktopLaunch-1.1.0.dmg'
```

通用预览版适用于 macOS 12 及以上，安装包包含 Apple 芯片和 Intel 二进制。打开 DMG 后，将桌面发射台拖到「应用程序」。点菜单栏的火箭图标即可试射。

预览版尚未通过 Apple 公证。首次打开若被拦截，可按 Apple 的说明为这个 App 单独授权。[Apple 支持](https://support.apple.com/zh-cn/102445)
