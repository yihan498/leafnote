# LeafNote

LeafNote 是一款简洁、本地优先的 Windows 与 macOS 桌面笔记软件。它以 ISO B5 等纸张尺寸组织页面，
支持横线纸、分页书写、阅读视图、文件夹分类、图片与表格，并将笔记保存为可迁移的 Markdown 文件。

## 下载

请在 [Releases](https://github.com/yihan498/leafnote/releases/latest) 下载：

- LeafNote-1.4.0-Windows-x64-Setup.exe：Windows x64 安装程序
- LeafNote-1.4.0-Windows-x64-Portable.exe：Windows x64 免安装程序
- LeafNote-1.4.0-macOS-Universal.dmg：macOS 11 及以上 Universal 安装镜像（Apple Silicon 与 Intel）
- LeafNote-1.4.0-macOS-Universal.app.zip：macOS Universal App 压缩包
- SHA256SUMS.txt：文件完整性校验

Windows 版本目前未进行代码签名，SmartScreen 可能显示“未知发布者”。macOS 版本采用临时
（ad-hoc）签名，尚未进行 Apple Developer ID 签名与公证；首次打开时可能需要前往“系统设置 →
隐私与安全性”选择“仍要打开”。请只从本仓库 Release 下载，并在运行前用 SHA256SUMS.txt
核对文件摘要。

## 数据与兼容

笔记保存在本机 Markdown 文件中。为兼容现有用户升级，内部应用标识、默认笔记目录和图片资源目录
继续沿用旧版本约定；升级到 LeafNote 不会自动迁移或删除原有笔记。

## 许可

LeafNote 使用 ISC License。第三方字体与参考项目的许可说明见 THIRD_PARTY_NOTICES.md，
完整第三方许可文本随每个正式 Release 提供。