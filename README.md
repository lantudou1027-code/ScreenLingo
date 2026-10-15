<p align="center">
  <img src="./ScreenLingo.png" width="160" alt="屏译图标">
</p>

# 屏译（ScreenLingo）

面向 macOS 的游戏字幕截图 OCR 与自动翻译工具。支持快捷键框选翻译，也支持固定区域持续识别；译文可作为可拖动、可缩放、可调透明度的字幕悬浮窗显示。

## 下载

当前版本：**0.3.2**

[下载 ScreenLingo-0.3.2-macOS.zip](https://github.com/lantudou1027-code/ScreenLingo/raw/refs/heads/main/ScreenLingo-0.3.2-macOS.zip)

系统要求：macOS 15.2 或更高版本，支持 Apple Silicon 与 Intel Mac。

## 安装

1. 下载并解压 ZIP，将 `ScreenLingo.app` 拖入“应用程序”。
2. 首次打开时，如果 macOS 拦截应用，请按住 Control 点击应用并选择“打开”。
3. 在“系统设置 → 隐私与安全性 → 屏幕与系统录音”中允许屏译，然后重新打开应用。
4. 按 `⌘⇧T` 框选屏幕文字，或在应用内启用固定区域自动翻译。

首次翻译某个语种时，macOS 可能会下载对应的系统语言包。OCR 在本机通过 Apple Vision 完成，翻译使用 Apple Translation 框架。

## 文件校验

`ScreenLingo-0.3.2-macOS.zip`

```text
SHA-256: 9e8acf3005e7b87b946b9bbaafec84d0914523784db8d3f693eecd2a26a74288
```

## 关于此仓库

此仓库仅用于公开分发屏译安装包，不包含源代码，也未提供开源许可证。
