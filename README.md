你可以直接打开网页免费使用它，它的功能是上传grid拼图，进行对齐、分割，并一键批量导出素材。针对 Banana Pro 等生图容易偏离中心的问题，你可以设置“内容缩放”和“对齐锚点”。例如：图片内容太大，可设为 90% 缩放；如果头顶被切，可选择“底部对齐”来拉低画面。直接点击下面网页可以使用: [[https://rabbitlin-web.github.io/Smart-Cropping-Tool-commonly-used-for-marking-/](https://rabbitlin-web.github.io/smart-crop-tool/)](https://rabbitlin-web.github.io/smart-crop-tool/)
如果帮到你了,请点个小星星哟~~
You can directly open the web page to use it for free, and its function is to upload grid puzzles, align, split, and export materials in batches with one click. To address the issue that raw images like Banana Pro tend to be off-center, you can set Content Scaling and Alignment Anchors. For example, if the image content is too large, it can be set to 90% zoom; If the top of the head is cut, select Bottom Alignment to lower the frame. Click directly on the following webpage to use:[ [https://rabbitlin-web.github.io/Smart-Cropping-Tool-commonly-used-for-marking-/](https://rabbitlin-web.github.io/smart-crop-tool/)](https://rabbitlin-web.github.io/smart-crop-tool/)
If it helps you, please click on a little star~~

这是一份为您定制的 **RabbitLin Smart Slicer 用户帮助手册 (User Manual)**。

采用了**中英文对照**的排版，清晰易读。您可以将这些内容放在 GitHub 的 `README.md` 中，或者做成一个单独的 `help.html` 页面链接到主页上。

-----

# 📘 RabbitLin Smart Slicer 用户手册 / User Manual

**全能型 AI 拼图切分神器 (图片 & GIF 动图)**
*The Ultimate AI Grid Slicer for Images & GIFs*

-----

## 1\. 💡 工具简介 / Introduction

**RabbitLin Smart Slicer** 是一款专为 AI 绘画创作者（Midjourney, Stable Diffusion, Banana Pro）设计的在线工具。它可以将 AI 生成的“九宫格”或“四格”拼图，一键智能切分为独立的高清素材。

**RabbitLin Smart Slicer** is a web-based tool designed for AI artists (Midjourney, Stable Diffusion, Banana Pro). It intelligently slices "Grid" images into individual high-quality assets with just one click.

### 核心用途 / Core Use Cases：

  * **🧪 LoRA 模型训练**：批量处理训练集，自动修复人物构图偏移。
      * *LoRA Training:* Batch process datasets and fix off-center subjects.
  * **🎨 漫画/分镜拆解**：将 MJ 生成的四格漫画拆分为独立画面。
      * *Comic/Storyboard:* Split 4-panel comics into individual frames.
  * **🎬 自媒体配图**：将方形图转为 16:9 或 9:16，用于视频封面或手机壁纸。
      * *Social Media:* Convert square grids to 16:9/9:16 for video thumbnails or wallpapers.
  * **👾 游戏素材**：切分精灵图 (Sprite Sheets) 或 Icon 图标集。
      * *Game Assets:* Slice sprite sheets or icon sets.

-----

## 2\. 🚀 核心优势 / Key Advantages

| 特性 (Feature) | 说明 (Description) |
| :--- | :--- |
| **🔒 隐私安全 (Privacy)** | **本地运行 (Local Processing)**：纯前端技术，图片绝不上传服务器，断网也能用。<br>*100% Client-side processing. Your images never leave your browser.* |
| **🖱️ 拖拽对齐 (Drag Align)** | **独创黄色手柄 (Yellow Handle)**：拖动一个点，全图自动缩放对齐，治愈强迫症。<br>*Drag the yellow handle to resize the entire grid instantly.* |
| **🎞️ GIF 动图支持 (GIF Support)** | 全网罕见支持 **GIF 动图切分**，保留动画帧，带实时进度条。<br>*Full support for animated GIFs with real-time processing progress.* |
| **📐 智能重构 (Smart Fix)** | **9点锚点 + 智能缩放**：人物画偏了？一键拉回 C 位，自动补全边缘。<br>*Fix off-center compositions using 9-point Anchors and Content Scaling.* |
| **🖥️ 任意比例 (Any Ratio)** | 支持导出 **16:9, 9:16, 1080P** 等多种尺寸，智能裁切不拉伸。<br>*Export in 16:9, 9:16, etc., with Smart Crop to prevent distortion.* |

-----

## 3\. 📖 使用指南 / Step-by-Step Guide

### 第一步：上传图片 / Step 1: Upload

点击虚线框，选择您的图片文件。

  * **支持格式**：JPG, PNG, WEBP, **GIF (动图)**。
  * *Click the upload area. Supports JPG, PNG, WEBP, and **GIF**.*

### 第二步：设置结构 / Step 2: Grid Structure

在 **"1. Grid Structure"** 面板中输入行列数。

  * 例如 Midjourney 默认是 2行 2列 (2x2)。
  * 例如 Banana Pro 常用 3行 5列 (5x3)。
  * *Input Columns and Rows (e.g., 2x2 for MJ, 5x3 for others).*

### 第三步：对齐网格 (重要) / Step 3: Alignment (Important)

这里有两种方式，推荐使用方式 A。

  * **方式 A：视觉拖拽 (Method 1: Visual Drag)**
    1.  在 **"Lock Aspect Ratio"** 下拉菜单中选择比例（如 1:1 或 16:9）。
    2.  **按住预览图中第一个红框右下角的“黄色小方块”**。
    3.  拖动它，直到红框完美覆盖第一张小图。
    <!-- end list -->
      * *Select an Aspect Ratio, then **drag the Yellow Handle** on the first red box until it fits perfectly.*
  * **方式 B：手动输入 (Method 2: Manual Input)**
      * 直接输入像素间距 (Gap X/Y) 进行微调。
      * *Input precise pixel values for Gap X/Y.*

### 第四步：导出设置 / Step 4: Export Settings

在 **"2. Export Settings"** 面板中调整：

1.  **Output Size (尺寸)**：选择想要的分辨率（如 1024x1024, 1920x1080）。
2.  **Resize Mode (模式)**：推荐选 **Smart Crop** (智能裁切，不变形)。
3.  **Smart Fix (微调)**：如果人物头顶被切，调整 **Anchor (锚点)** 到 Bottom，或缩小 **Zoom**。

<!-- end list -->

  * *Select Output Size and Mode (Smart Crop recommended). Use Zoom & Anchor to fix composition.*

### 第五步：下载 / Step 5: Download

点击 **"Start Processing"**。

  * **静态图**：瞬间完成，自动下载 ZIP。
  * **GIF 动图**：请耐心等待进度条走完，处理完成后自动下载。
  * *Click Start. Static images are instant. For GIFs, please wait for the progress bar.*

-----

## 4\. ⚠️ 常见问题 / FAQ

**Q: 下载的 ZIP 文件在 Windows 上解压报错？**
**A:** 这是 Windows 自带解压功能的已知 Bug。请使用 **7-Zip** 或 **Bandizip** 等第三方软件解压，或者右键文件属性勾选“解除锁定(Unblock)”。

  * *Windows Explorer may report an error. Please use **7-Zip** or **Bandizip** to extract.*

**Q: GIF 处理为什么比较慢？**
**A:** GIF 包含几十甚至上百帧。工具需要拆解每一帧、分别裁切重构再重新组装。这是在消耗您本地电脑的性能，请耐心等待进度条。

  * *GIFs contain many frames. The tool processes each frame locally on your device, which takes time.*

**Q: 预览图为什么是黑色的？**
**A:** 请检查您是否上传了图片。如果是 GIF 模式，请等待解析完成。

  * *Please ensure an image is uploaded. For GIFs, wait for the parser to finish.*

-----

**Designed with ❤️ by RabbitLin**
*如果觉得好用，请在 GitHub 给个 Star！*
*If you like it, please give us a Star on GitHub\!*
