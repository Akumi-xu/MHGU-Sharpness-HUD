# 斩味条 HUD

- [斩味条-主机模式.zip](02_build/%E6%88%90%E5%93%81MOD/%E6%96%A9%E5%91%B3%E6%9D%A1HUD/%E6%96%A9%E5%91%B3%E6%9D%A1-%E4%B8%BB%E6%9C%BA%E6%A8%A1%E5%BC%8F.zip)
- [斩味条-掌机模式.zip](02_build/%E6%88%90%E5%93%81MOD/%E6%96%A9%E5%91%B3%E6%9D%A1HUD/%E6%96%A9%E5%91%B3%E6%9D%A1-%E6%8E%8C%E6%9C%BA%E6%A8%A1%E5%BC%8F.zip)
- [斩味条L + 十字键下 + Y可调整版.zip](02_build/%E6%88%90%E5%93%81MOD/%E6%96%A9%E5%91%B3%E6%9D%A1HUD/%E6%96%A9%E5%91%B3%E6%9D%A1L%20+%20%E5%8D%81%E5%AD%97%E9%94%AE%E4%B8%8B%20+%20Y%E5%8F%AF%E8%B0%83%E6%95%B4%E7%89%88.zip)

[完整源码与功能说明](01_plugins/sharpness_hud/)。包内提供安装说明；安装包按原样保存。

构建：克隆到纯 ASCII 路径，准备 Rust nightly、rust-src、cargo-mhgu-forge 1.5.0、ARM GNU Toolchain 和 Python 3。进入本目录后运行：

```powershell
powershell -NoProfile -ExecutionPolicy Bypass -File .\01_plugins\sharpness_hud\make_release.ps1
```

2026-11-14 上传已有安装包与当前源码快照；ZIP 完整性及包内 NRO 重定位检查通过，本次未重新编译或进行游戏测试。Eden / Switch 需要另装兼容的 Forge 前置；源码快照不保证与历史二进制逐字节复现。三个斩味条版本只能安装一个。
