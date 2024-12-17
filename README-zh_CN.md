# Yet Another Favicon Downloader

[![GitHub release](https://img.shields.io/github/release/navossoc/KeePass-Yet-Another-Favicon-Downloader.svg)](https://github.com/navossoc/KeePass-Yet-Another-Favicon-Downloader/releases/latest)
[![license](https://img.shields.io/github/license/navossoc/KeePass-Yet-Another-Favicon-Downloader.svg)](/LICENSE)

## 目录

- [简介](#简介)
  - [特色](#特色)
- [需求](#需求)
- [安装](#安装)
- [使用方法](#使用方法)
- [更新日志](#更新日志)
- [贡献](#贡献)
- [版权与许可](#版权与许可)

## 简介

_Yet Another Favicon Downloader_（简称_YAFD_）是 _KeePass_ 2.x 的一个插件，可让您快速下载密码条目的图标。

### 特色

- 并发响应（可加快下载速度而不会冻结用户界面）
- 轻便可靠（可用于批量下载数千个图标）
- 智能高效
  - 避免图标重复（可重复使用数据库中已有的自定义图标）
  - 下载没有网址格式的条目（自动在网址前添加 `http://` 前缀）
  - 下载不带网址字段的条目（自动使用“标题”字段）
  - - 自动调整图标大小（缩放至 128x128 px）
- 支持Linux（_实验性_）
- 支持代理（跟随 _KeePass_ 设置）
- 现代支持（在 .NET 4.8 上支持 TLS 1.3）

## 需求

- _KeePass_ 2.34 或更新。

### Linux

- _Mono_ 4.8.0 或更新。

更多安装说明请访问 [wiki](https://github.com/navossoc/KeePass-Yet-Another-Favicon-Downloader/wiki/Linux-install)。

### Windows

- _.NET Framework_ 4.8 或更新。

## 安装

- 下载[最新的](https://github.com/navossoc/KeePass-Yet-Another-Favicon-Downloader-zh_CN/releases/latest)Release
- 将 _YetAnotherFaviconDownloader.plgx_ 复制到 _KeePass_ 插件文件夹中
- 重新启动 _KeePass_ 以加载插件

## 使用方法

此插件在 _KeePass_ 的条目和组右键菜单中添加了一个名为**“Download Favicons”**（“下载图标”）的新菜单项。

选择一个或多个条目，然后单击 _Download Favicons_ 下载与该_网址_相关的_图标_。

![Entry Context Menu](docs/images/entry-context-menu.gif)

---

您也可以选择一个组，然后单击 _Download Favicons_ 为该组及其子组中的所有条目下载_图标_。

![Group Context Menu](docs/images/group-context-menu.gif)

## 更新日志

有关每个版本的详细信息，请参阅[Releases](https://github.com/navossoc/KeePass-Yet-Another-Favicon-Downloader/releases)部分。

## 贡献

发现了错误？

请先尝试[原版](https://github.com/navossoc/KeePass-Yet-Another-Favicon-Downloader)是否有同样的问题。若有，请[在原仓库中搜索打开和已关闭的issue](https://github.com/navossoc/KeePass-Yet-Another-Favicon-Downloader/issues?q=is%3Aissue)；若没有，请[打开一个新issue](https://github.com/navossoc/KeePass-Yet-Another-Favicon-Downloader/issues/new)。

如果问题无法在原版中复现，请[在本仓库中搜索打开和已关闭的issue](https://github.com/CJYKK/KeePass-Yet-Another-Favicon-Downloader-zh_CN/issues?q=is%3Aissue)；若没有，请[打开一个新issue](https://github.com/CJYKK/KeePass-Yet-Another-Favicon-Downloader-zh_CN/issues/new)。

## 版权与许可

_Yet Another Favicon Downloader_ source code is licensed under the [MIT License](LICENSE).

[Documentation](docs/README.md) is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

Other [Resources](Resources/README.md) are separately licensed.

When you contribute to this repository you are doing so under the above licenses.
