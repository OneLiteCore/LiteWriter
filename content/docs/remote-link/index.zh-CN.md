---
ShowToc: true
aliases:
- zh-CN/docs/remote-link/
copy_mark: src
date: 2024-05-25
title: 如何使用“连接”功能?
url: /zh-CN/docs/remote-link/
---

“连接”功能可以将你的应用数据映射为 PC 上的一个文件夹，使得你可以用 PC 的软件来编辑你的文本。

该功能基于通用的 WebDav 协议实现，你可以使用操作系统自带的映射逻辑或者任何你熟悉的第三方工具来完成映射。以下简单介绍部分较为简便的映射方式。

## Windows

在 Windows 平台这里推荐使用 RaiDrive 这款第三方工具。你可以通过下方的地址来下载安装包：

[RaiDrive 1.8.0 https://raidrive.en.uptodown.com/windows/download/2114805](https://raidrive.en.uptodown.com/windows/download/2114805)

（1.8.0 并不是最新版，但它功能齐全更重要的是它没有广告）

安装打开后你可以看到如下界面，接着按照下面步骤操作：

![RaiDrive setup](/img/add_drive.zh-CN.webp)

1. 点击顶部“添加”按钮进入映射配置流程
2. 选择“NAS”并选中“WebDav”协议
3. 选择映射文件夹的硬盘符和名称
4. 输入映射地址
    - 在“地址”字样的右侧你可以看到一个复选框，该框是用于切换 http 和 https 协议的，**请确保它处于未选中的状态**，此时协议未 **http**
    - 输入到右侧的地址栏和端口号。截图中的地址和端口仅供参考，请以启动应用“连接”功能后界面显示的为准。
    - “路径”一栏可以留空
5. 输入你自定义的用户名和密码，如果没有的话可以勾选“匿名”复选框
6. 点击“确定”按钮以启动映射

如果一切顺利则在成功后会自动打开映射目录，如下图所示：

![Done](/img/done.zh-CN.webp)

## Linux 或者 MacOS

待补充
