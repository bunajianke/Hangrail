# Hangrail

Hangrail 是一款适用于 macOS 和 Windows 的剪贴板与文件中转工具，支持顶部悬挂卡片和底部卡片面板。

此仓库用于发布安装包、版本说明和应用更新信息。源代码暂不在此仓库公开。

## 下载

请前往 [Releases](https://github.com/bunajianke/Hangrail/releases) 选择对应平台和架构的安装包。

- macOS：当前提供 Apple Silicon（ARM64）版本。
- Windows：提供 ARM64 和 x64 的 MSIX 安装包。

## 在线更新

安装含在线更新功能的版本后，可在 Hangrail 菜单或“设置 → 通用 → 软件更新”中检查更新。更新会保留资料库和设置，安装前会要求确认。默认每天检查新版本。

更新包使用固定的应用签名身份。macOS 还验证独立的 Ed25519 更新签名；Windows 验证安装包签名、包身份、架构及文件摘要。

当前为开发签名体验版。首次在新电脑安装时仍需满足系统的签名与信任要求。请勿关闭系统安全检查。
