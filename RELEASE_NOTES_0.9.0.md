# CompoSe v0.9.0 Public Beta

首个 Apple Silicon 公开测试版本，支持 macOS 14 及以上。

## 主要功能

- 在一个画布中组合图片、视频和文字
- 图片等比匹配视频宽度或高度
- 同时播放与顺序播放
- 导出当前组或连续导出全部视频组
- 固定分辨率和跟随画布输出
- 项目保存与可选的本地 Git 版本记录

## 安装

下载 `CompoSe-0.9.0-Apple-Silicon.dmg`，打开后把 CompoSe 拖到 Applications。

本版本使用临时代码签名，未经过 Apple Developer ID 验证和公证。首次启动时：

1. 尝试打开 CompoSe 一次。
2. 进入“系统设置 → 隐私与安全性”。
3. 找到 CompoSe，点击“仍要打开”并确认。

请同时下载 SHA-256 文件并校验安装包：

```bash
shasum -a 256 -c CompoSe-0.9.0-Apple-Silicon.dmg.sha256
```

---

This is the first Apple Silicon public beta for macOS 14 or later. It includes
mixed image and video composition, aspect-ratio-preserving size matching,
grouped playback, continuous all-group export, configurable output resolution,
project saving, and optional local Git history.

Download `CompoSe-0.9.0-Apple-Silicon.dmg`, open it, and drag CompoSe to
Applications.

This build uses an ad-hoc code signature and has not been verified or notarized
by Apple. On first launch, try to open CompoSe once, then go to System Settings
→ Privacy & Security and click Open Anyway for CompoSe.

Download the accompanying checksum file and verify it with:

```bash
shasum -a 256 -c CompoSe-0.9.0-Apple-Silicon.dmg.sha256
```
