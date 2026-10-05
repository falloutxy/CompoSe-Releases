# CompoSe v0.10.0 Public Beta

本次更新把 CompoSe 的画布升级为真正的多图层合成工作区，并重点修复预览与导出不一致的问题。

## 新功能

- 支持图层左右、上下、网格和重叠排列，排列时相邻图层零间隔
- 支持图层前后顺序、画布内位置交换和像素级微调
- 支持横向／竖向 Alpha 分屏遮罩、分割线旋转、速度、方向和循环控制
- 循环擦除／揭示保持同一运动方向，奇偶周期交替揭示与擦除
- 文本支持字号、颜色、可拖拽调整的文本框，以及与媒体图层建立链接
- 自动画布实时完整包裹图层和文字，提供完整居中、鼠标滚轮缩放和中键平移

## 修复与改进

- 修复播放视频时遮罩消失
- 修复文字换行或改变字号后被文本框裁切，以及部分中文输入问题
- 修复链接文字移出父图层后不可见
- 修复旋转遮罩无法完全擦除或揭示画面
- 修复导出视频上下颠倒、分辨率与画布不一致及额外黑边
- 统一暂停、播放、时间拖动和导出的图层顺序、遮罩与文本渲染结果
- 排列或首次进入画布时完整居中，普通编辑过程中保持视口稳定

## 安装

下载 `CompoSe-0.10.0-Apple-Silicon.dmg`，打开后把 CompoSe 拖到 Applications。

本版本面向 Apple Silicon Mac，要求 macOS 14 或更高版本。它使用临时代码签名，未经过 Apple Developer ID 验证和公证。首次启动时，请先尝试打开一次，然后进入“系统设置 → 隐私与安全性”，找到 CompoSe 并点击“仍要打开”。

请同时下载 SHA-256 文件并校验安装包：

```bash
shasum -a 256 -c CompoSe-0.10.0-Apple-Silicon.dmg.sha256
```

---

This update turns CompoSe into a multi-layer composition workspace and focuses on keeping canvas preview and exported output consistent.

## Highlights

- Side-by-side, vertical, grid, and overlapping layer arrangements with zero preset spacing
- Layer stacking controls, spatial swapping, and pixel nudging
- Horizontal and vertical alpha split masks with rotation, speed, direction, and looping wipe/reveal controls
- Same-direction looping wipes that alternate reveal and erase phases without reversing travel
- Text size, color, resizable text boxes, and links to media layers
- Automatic content bounds, fit-all view, pointer-anchored wheel zoom, and middle-button pan
- Fixes for mask playback, text clipping, linked-text visibility, export orientation, resolution, and black borders

Download `CompoSe-0.10.0-Apple-Silicon.dmg`, open it, and drag CompoSe to Applications. This Apple Silicon beta requires macOS 14 or later, uses an ad-hoc signature, and is not notarized by Apple.
