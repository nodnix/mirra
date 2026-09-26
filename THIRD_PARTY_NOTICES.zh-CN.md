# Mirra 第三方软件声明

简体中文 | [English](THIRD_PARTY_NOTICES.md)

Mirra 是闭源产品，但包含按独立许可证提供的第三方软件。第三方组件的版权属于其各自权利人；相应许可证不因 Mirra 的产品条款而失效。

## 主要组件

- **Qt 6.10.2**：使用 LGPL-3.0 开源许可选项，采用动态链接方式分发。实际模块和插件以对应平台安装包中的许可材料为准。
- **FFmpeg 7.1.2**：Qt Multimedia 后端可能分发 FFmpeg 运行库；发布构建按 LGPL-2.1-or-later 方案准备，不使用 GPL 或 nonfree 构建替代。
- **Fraunhofer FDK AAC 2.0.3**：Windows 版本用于解码 AAC-ELD 音频，适用其原始许可声明；该许可不授予专利许可。
- **Go 及 Go 依赖**：适用 Go 项目和各依赖分别提供的许可证。

## 完整材料

每个平台的正式发布包均应包含完整的第三方版权声明、许可原文、对应源码获取方式，以及适用时的库替换说明：

- macOS：`Mirra.app/Contents/Resources/licenses/`
- Windows：Mirra 便携版解压目录中的 `licenses/`

本页只是便于阅读的概要，不能替代发布包内的完整许可材料。具体版本、实际分发组件和原始许可证以对应 Release 发布包为准。

第三方软件的修改、替换、重新链接及相关调试权利见 [开源软件权利](OPEN_SOURCE_RIGHTS.zh-CN.md)。
