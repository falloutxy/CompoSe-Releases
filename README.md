<p align="center">
  <img src="assets/AppIcon.png" width="160" alt="CompoSe icon">
</p>

# CompoSe

CompoSe 是一款面向 macOS 的轻量图片与视频画布编辑器。它可以把多张图片、视频和
文字组合到同一画布，按组预览，并导出静态图片或连续视频。

> **v0.9.0 Public Beta** 现已开放下载。这是未经过 Apple Developer ID
> 验证和公证的测试版本。

## 下载与安装

- 系统要求：Apple Silicon Mac，macOS 14 或更高版本。
- 从 [v0.9.0 Public Beta](https://github.com/falloutxy/CompoSe-Releases/releases/tag/v0.9.0)
  下载 `CompoSe-0.9.0-Apple-Silicon.dmg`。
- 打开 DMG，把 CompoSe 拖到 Applications，然后从“应用程序”启动。
- 首次启动时，macOS 会提示无法验证开发者。尝试打开一次后，进入“系统设置 →
  隐私与安全性”，找到 CompoSe 并点击“仍要打开”。确认后即可正常启动。
- 本测试版本未经过 Apple 公证，请只从本仓库下载并核对 SHA-256。
- 每个版本同时提供 SHA-256 文件，可用以下命令校验：

  ```bash
  shasum -a 256 -c CompoSe-0.9.0-Apple-Silicon.dmg.sha256
  ```

## 主要功能

- 图片、视频和文字在同一画布自由组合
- 图片保持宽高比匹配视频显示宽度或高度
- 同时播放与顺序播放模式
- 当前组或全部视频组导出
- 固定分辨率或跟随画布输出
- 项目保存与本地 Git 版本记录

问题和建议请提交到 [Issues](https://github.com/falloutxy/CompoSe-Releases/issues)。
安全问题请勿创建公开 Issue，请按照[安全政策](SECURITY.md)私下报告。

CompoSe 只在本机处理用户选择的媒体文件，不包含遥测或媒体上传服务。只有用户主动
使用项目 Git 功能时，Git 才会访问该项目自行配置的远程仓库。

源码不公开。本仓库中的 GitHub 自动源码压缩包只包含下载说明和发布资料，不包含
CompoSe 应用源码。软件使用受 [专有许可](LICENSE.txt) 约束。

---

## English

CompoSe is a lightweight macOS canvas editor for arranging images, videos, and
text in one composition. It supports grouped playback and exports still images
or continuous video across multiple groups.

> **v0.9.0 Public Beta** is now available. This test build does not have Apple
> Developer ID verification or notarization.

### Download and install

- Requirements: Apple Silicon Mac with macOS 14 or later.
- Download `CompoSe-0.9.0-Apple-Silicon.dmg` from
  [v0.9.0 Public Beta](https://github.com/falloutxy/CompoSe-Releases/releases/tag/v0.9.0).
- Open the DMG, drag CompoSe to Applications, and launch it from Applications.
- On first launch, macOS will report that the developer cannot be verified.
  After trying to open the app once, open System Settings → Privacy & Security,
  find CompoSe, and click Open Anyway.
- This beta has not been notarized by Apple. Download it only from this
  repository and verify its SHA-256 checksum.
- Verify the accompanying checksum with:

  ```bash
  shasum -a 256 -c CompoSe-0.9.0-Apple-Silicon.dmg.sha256
  ```

### Highlights

- Arrange images, videos, and text on one canvas
- Match image width or height to video while preserving aspect ratio
- Simultaneous and sequential playback modes
- Export the current group or all groups as one continuous video
- Fixed output resolution or follow-canvas sizing
- Project saving and optional local Git history

Please use [Issues](https://github.com/falloutxy/CompoSe-Releases/issues) for
bugs and feature requests. Do not post security reports publicly; follow the
[security policy](SECURITY.md) to report them privately.

CompoSe processes selected media locally and contains no telemetry or media
upload service. Git accesses a remote only when the user explicitly uses the
project Git feature and that project has a remote configured.

The application source code is private. GitHub-generated source archives for
this repository contain only download documentation and release metadata. Use
of the software is governed by the [proprietary license](LICENSE.txt).
