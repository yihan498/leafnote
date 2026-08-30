# LeafNote

LeafNote 是一款简洁、本地优先的 Windows 桌面笔记软件。它以 ISO B5 等纸张尺寸组织页面，
支持横线纸、分页书写、阅读视图、文件夹分类、图片与表格，并将笔记保存为可迁移的 Markdown 文件。

## 下载

请在 [Releases](https://github.com/yihan498/leafnote/releases/latest) 下载：

- LeafNote-1.3.15-Windows-x64-Setup.exe：Windows 安装程序
- LeafNote-1.3.15-Windows-x64-Portable.exe：免安装可执行文件
- SHA256SUMS.txt：文件完整性校验

LeafNote 目前未进行代码签名。Windows SmartScreen 可能显示“未知发布者”提示；请只从本仓库
Release 下载，并在运行前用 SHA256SUMS.txt 核对文件摘要。

## 数据与兼容

笔记保存在本机 Markdown 文件中。为兼容现有用户升级，内部应用标识、默认笔记目录和图片资源目录
继续沿用旧版本约定；升级到 LeafNote 不会自动迁移或删除原有笔记。

## 许可

LeafNote 使用 ISC License。第三方字体与参考项目的许可说明见 THIRD_PARTY_NOTICES.md，
完整第三方许可文本随每个正式 Release 提供。