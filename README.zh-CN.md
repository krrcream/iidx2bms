# iidx2bms fork

简体中文 · [English](README.md)

这是我对 [iidx2bms](https://github.com/Glebsin/iidx2bms) 的个人 fork，**仅**作为我自己本地运行的
[LR2oraja Endless Dream](https://github.com/seraxis/lr2oraja-endlessdream) 环境的内部组件保留。
本仓库与上述两个项目均无从属关系，也不供他人使用。

## 分支

- **`orajaroot`**：LDJ 侧使用的插件依赖，保持只读、不作改动。
- **`orajaroot-plus`**：LDJPlus 直读改造用的分支，本 README 描述的对象。

## 这个分支是什么

`orajaroot-plus` 是上游项目的精简、无交互版本：去掉了 GUI 程序、打包脚本与图标，以及未使用的
`ifs_unpack` 模块。

运行依赖：

- `ifstools`：Python 外部依赖，需另行安装（`pip install ifstools`）
- `ffmpeg/ffmpeg.exe`：体积过大未纳入版本库，需自行放置；仅当旧式 `.s3p` 含 WMA 键音时才用到

## 版权声明

- 本仓库不提供任何用于破解、绕过或解密任何保护或加密的补丁、密钥或方法。
- 本仓库不提供获取游戏数据的链接或相关信息。
- 本仓库不提供安装、使用、转换或排错教程。
- 本仓库不对其中任何部分授予许可。我对其中包含或引用的第三方及游戏衍生内容不主张任何权利：
  这些内容的权利均归各自权利人所有，本仓库不对其进行授权、分发或支持。
- 上游 iidx2bms 及随其附带的辅助工具，权利归各自作者所有。

> [!CAUTION]
> 请勿使用本程序游玩未经许可的版权内容。
