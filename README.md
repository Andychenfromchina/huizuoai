# 汇作AI · 安装包下载

本仓库用于分发汇作AI桌面端安装包、版本说明和 SHA-256 校验文件，不用于存放产品源码、用户数据或凭据。

## 下载

请前往 [Releases](https://github.com/Andychenfromchina/huizuoai/releases) 选择版本，并下载该版本 **Assets** 中的安装包及 `SHA256SUMS.txt`。GitHub 自动生成的 `Source code` 压缩包不是安装包。

适用芯片、最低系统版本、安装步骤、已知问题以及签名和公证情况，以每个 Release 的说明为准。预览版本会标记为 Pre-release；签名或公证通过不等同于全部业务功能已完成验收。

最新公开预览版：[汇作AI R68 · Build 87 · 0.1.7-rc.2](https://github.com/Andychenfromchina/huizuoai/releases/tag/v0.1.7-rc.2-r68-build87-bd32a22)，适用于 macOS 13.0 及以上的 Apple Silicon 设备。

[下载安装包（ZIP）](https://github.com/Andychenfromchina/huizuoai/releases/download/v0.1.7-rc.2-r68-build87-bd32a22/HuiZuoAI-0.1.7-rc.2-R68-build87-bd32a22-macOS-arm64.zip) · [SHA-256 校验文件](https://github.com/Andychenfromchina/huizuoai/releases/download/v0.1.7-rc.2-r68-build87-bd32a22/SHA256SUMS.txt)。

## 校验下载

在 macOS 终端运行 `shasum -a 256`，后面填写下载的安装包路径。将输出摘要与该版本附带的 `SHA256SUMS.txt` 对照，确认完全一致后再安装。

若校验不一致，请勿安装，也不要通过关闭系统安全检查绕过错误。
