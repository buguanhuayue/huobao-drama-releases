# 火宝短剧桌面版

本仓库长期公开，用于分发桌面安装包及应用更新文件，下载无需 GitHub 登录。源码在独立仓库维护。

## 下载

请前往 [Releases](https://github.com/buguanhuayue/huobao-drama-releases/releases) 下载对应系统的安装包：

- Windows x64：EXE 安装包。
- Mac Apple Silicon：DMG 安装包；ZIP 用于正式签名版本的自动更新。
- Intel Mac 安装包暂未提供。

运行不需要 Docker、MySQL、Node、Python 或 FFmpeg；桌面程序内置所需运行时。AI 生成服务仍需在应用内配置。

## 更新

旧 1.0.0 / 私有发布的 1.1.0 安装包，需要手动覆盖安装 1.1.1 一次，使更新地址迁移到本仓库。配置、项目和媒体保留在用户数据目录。

1.1.1 起可匿名检查更新。Windows 可在应用内下载安装并重启，安装前等待后台任务结束并备份数据。Mac 当前可检查和下载更新，退出应用后用 DMG 手动覆盖安装；正式签名和公证后可以启用自动安装。

`desktop-stable` Release 保存各平台更新入口；`desktop-v版本号` Release 保存对应安装包及校验文件。

## 当前测试状态

当前安装包为内部测试版。Windows 尚未正式代码签名或完成实机覆盖安装验收；Mac 使用 ad-hoc 签名，未公证。详细范围见版本发布说明。
