# PiliPlus 独立版

基于 [PiliPlus 上游](https://github.com/bggRGjQaUbCoE/PiliPlus) 和 [原定制版](https://github.com/lkhr1722253349-maker/PiliPlus) 构建，沿用 GPLv3 授权。

Android 包名为 `com.example.piliplus.standalone`，拥有独立签名和应用数据，可与原定制版并存。应用内更新使用 [本仓库 Releases](https://github.com/lkhr1722253349-maker/PiliPlus-Standalone/releases)。

仓库只维护上游版本锁、补丁和构建配置。在干净的完整临时检出里运行 `pwsh -File scripts/assemble.ps1` 可合成完整源码，随后按合成目录中的 `CUSTOMIZATION.md` 构建。正式发布须使用同一把独立版签名密钥。
