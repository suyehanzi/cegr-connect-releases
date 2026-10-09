# 橙格 · AI 环境助手

## Mac v1.0.0

**[下载 Mac v1.0.0](https://github.com/suyehanzi/cegr-connect-releases/releases/download/v1.0.0/CEGR-AI-Assistant-v1.0.0-for-macOS-arm64.zip)** · [版本说明](https://github.com/suyehanzi/cegr-connect-releases/releases/tag/v1.0.0)

适用于 **Apple 芯片 Mac，macOS 14 或更新版本**。安装包已通过 Developer ID 签名和 Apple 公证，主程序和保护组件为 1.0.0（57）。本仓库 Releases 仅保留 v1.0.0。

### 安装与激活

1. 下载 ZIP 并解压，将「橙格 · AI 环境助手」拖入“应用程序”。
2. 打开助手，按提示登录账号、兑换卡密、导入自己的代理连接。
3. 完成网络扩展、网络过滤和应用连接设置。系统密码由本人输入。
4. 在「本机状态 → 查看保护检查」核对组件与应用设置，再检查实际连接。

Mac 客户版自带保护组件，无需另装 LuLu。请使用安装包附件；Source code 不是安装包。

### 软件更新

打开「更多工具 → 软件更新」检查新版，在应用内下载并确认安装；也可以使用本页 GitHub 下载链接。更新前请保存工作，升级本身不消耗新卡密。

0.5.30 内测版可检查到 1.0.0；更早内测版请手动安装。保留原账号、连接记录及偏好，勿清空数据或点击“恢复原配置”。旧版专用连接正在运行时，先在助手中暂停连接，再正常退出助手并覆盖安装；重新打开后按提示恢复连接。

若出现“更新保护组件”，请保存并退出所选应用，在检查面板内完成更新及系统提示。保持现有 Clash/TUN 设置。

### 验证范围与支持

本台已验证安装、组件匹配和固定出口核验；Claude Code 的一次有界阻断与恢复及隔离更新替换已有实测记录。**逐应用断网保护、登录／重启恢复和本次更新后的完整重启验收仍未全部完成。** 部分 Chrome 检测请求曾出现客户端拦截，仍需复验。应用“设置匹配”不代表全部保护测试通过。

发生问题时，请从助手复制检查摘要，通过原购买订单联系橙格客服。代理能否多设备同时使用取决于供应商规则。请勿公开卡密、密码和代理凭据。

## Windows 内测

Windows 继续保持 **0.5.30 内测**，不属于 Mac 1.0.0 正式发布范围。

[下载 Windows 10/11 x64 内测安装器](https://shop.cegr.si/downloads/cegr/windows/preview/0.5.30/CEGR-AI-Assistant-v0.5.30-for-Windows-10-11-x64-Setup.exe) · [校验值](https://shop.cegr.si/downloads/cegr/windows/preview/0.5.30/SHA256SUMS.txt)

完整应用保护、防旁路和配置恢复仍未全部集成。安装器尚无发布者签名；原生测试环境为 Windows Server 2022，客户 Windows 10/11 设备仍需验收。旧 GitHub 内测版本已退役，需重装时请使用上方独立下载入口。

本仓库仅提供公开安装包、说明、签名更新信息和校验值，不包含项目源码或客户资料。
