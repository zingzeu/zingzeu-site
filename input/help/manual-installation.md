Title: 手动安装教程（高级用户）
MachineName: manual-installation
---

> 此为临时的手动安装方法。我们推荐初级用户等待自动安装器开发完成，或使用[网页体验版](http://yngping.mindong.asia)。
> 
> 手动安装方法有局限性。不能自动更新。请加入内测 QQ 群（770807471）来获取最新版本信息。

#### 概述

真鸟囝输入法基于 [RIME](https://rime.im)。手动安装方法需要你先在电脑上自行安装 RIME 输入法，然后手动导入真鸟囝词库。

#### 安装 RIME

请按照 RIME [官方教程](https://rime.im/download/)下载和安装小狼毫（Windows）、鼠鬚管（macOS）、同文輸入法（Android）。iOS 平台可使用 [iRime](https://apps.apple.com/cn/app/irime输入法/id1142623977)。

如需帮助，请参考 RIME 官方[帮助文档](https://rime.im/docs/)、同文輸入法官方[维基教程](https://github.com/osfans/trime/wiki/UserGuide)、iRime [自定义教程](http://wiki.5koon.com/doku.php?id=customisationsim)。

#### 下载和导入真鸟囝词库

1. 下载[最新词库](https://wj.qq.com/s2/5329731/6d93/)

1. 将下载的压缩包解压缩。

1. 打开 RIME 的“用户文件夹”。

   * Windows 用户：开始菜单 -> 小狼豪输入法 -> 【小狼豪】用户文件夹。或打开 `%APPDATA%\Rime`
   * macOS 用户：打开终端 (Terminal)，运行 `open ~/Library/Rime/`
   * Android 用户：文件管理器 -> `rime` 文件夹
   * iOS 用户：打开 “iRime” 应用 -> 电脑快传

1. 将解压缩完的文件，拖拽/复制到 RIME 用户文件夹。

   <img src="/assets/images/manual-install-copy.jpg" alt="将解压缩完的文件复制到 RIME 用户文件夹" style="max-width: 400px;"/>
   
   * iOS 用户：iRime 需要导入更多配置文件。请参考 iRime 自定义教程。

1. 激活真鸟囝输入法。
   
   * Windows 用户：开始菜单 -> 小狼豪输入法 -> 【小狼豪】输入法设定 -> 勾选 “平话（福州市区）” -> 点击 “中”

    <img src="/assets/images/manual-install-activate.jpg" alt="将解压缩完的文件复制到 RIME 用户文件夹" style="max-width: 400px;"/>

   * macOS 用户：用文本编辑器打开 `~/Library/Rime/default.yaml`，在 `schema_list` 下新增一行：
    ```
      - schema: Hukziu
    ```
    
   * Android 用户：打开 “同文输入法” 应用 -> 选取软键盘 -> 选取 “同文输入法”
   * iOS 用户：返回 “桌面” -> 设定 -> 一般 -> 键盘 -> 选取 “iRime”
   
   
1. 重新部署RIME。
   
   * Windows 用户：开始菜单 -> 小狼豪输入法 -> 【小狼豪】重新部署
   * macOS 用户：切换到鼠鬚管输入法，点击屏幕右上角的鼠鬚管图标，然后点 “部署(Deploy)”
   * Android 用户：打开 “同文输入法” 应用 -> 部署
   * iOS 用户：打开 “iRime” 应用 -> 部署

1. 将系统输入法切换到小狼豪/鼠鬚管/同文輸入法/iRime，按下 `` Ctrl-` `` 、 `F4` 或相关图标，切换到 “平话（福州市区）”

#### 更新词库

需要更新时，重复以上步骤，覆盖旧文件。

#### 同步输入习惯

通过 RIME 输入法手动安装真鸟囝词库，默认不支持多终端同步。可借助同步软件实现端与端之间 RIME 用户文件夹的同步。如为用户文件夹生成 WebDAV 本地共享目录，并使用支持 WebDAV 协议的软件同步等。
