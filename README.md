# AuralCanvas - Apple Music 专辑封面下载工具

<p align="center">
  <img src="docs/note.png" width="120" height="120" alt="AuralCanvas Logo">
</p>

<p align="center">
  <a href="https://ko-fi.com/O5O81QNNWN" target="_blank">
    <img src="https://ko-fi.com/img/githubbutton_sm.svg" alt="在 Ko-fi 上支持我">
  </a>
</p>

[English](#english) | [简体中文](#chinese)

---

<a name="english"></a>

## 🚀 English Version

### 🌟 Introduction

**AuralCanvas** is a powerful, lightweight web tool designed for music enthusiasts and collectors. It allows you to easily fetch and download high-quality artworks from Apple Music, including static covers, banners, and 4K animated covers.

Our tool pulls data directly from Apple Music's servers using a hybrid approach — combining the iTunes Search API for fast metadata retrieval with HTML scraping for additional assets like animated covers and banners. All downloads are free, no registration required.

### ✨ Key Features

- **High Resolution**: Get ultra-high-resolution album covers (up to 100000×100000 pixels).
- **Animated Artwork**: Download 4K motion artwork in MP4 format.
- **Smart Search**: Search by keyword or paste an Apple Music link.
- **Custom Size**: Resize downloads to any dimension you need.
- **Timestamp Fix**: Automatic FFmpeg-based correction for animated cover playback issues.
- **No Registration Required**: Access directly from Apple Music servers.
- **Multi-Language**: Supports English, Chinese, and Japanese.
- **Theme Support**: System, Light, and Dark modes.

### 🌐 Official Websites

- [auralcanvas.xyz](https://auralcanvas.xyz)
- [coverfetcher.xyz](https://coverfetcher.xyz)

### ⚡ How It Works

1. **Search** — Enter keywords or paste an Apple Music link.
2. **Select Artwork** — Choose from static covers, banners, or motion artworks.
3. **Download High-Res** — Save uncompressed 4K artwork directly to your device.

### 📸 User Guide

#### 🔍 1. The Main Interface

- **Region Selector**: Tap the globe icon to switch between Apple Music storefronts. Supported regions include: US, UK, China, Japan, Germany, France, Canada, Australia, Hong Kong, Taiwan, and South Korea.
- **Language Switcher**: Toggle between English, Chinese, and Japanese at the top right.
- **Theme Toggle**: Switch between System, Light, and Dark modes.

![Main Interface](docs/screenshots/main_interface_en.png)

#### ⌨️ 2. Search & Fetch

- **Keyword Search**: Type the name of an album, artist, or song.
- **Direct Link Fetching**: Paste an Apple Music link (e.g., `https://music.apple.com/...`).

![Search Results](docs/screenshots/search_results_en.png)

#### 🖼️ 3. Comprehensive Entity Support

Whether you're looking for an album or a music video, we've got you covered:

- **Albums & Songs**: Get square covers in maximum quality.
  ![Album Results](docs/screenshots/entity_album_en.jpeg)
- **Playlists & Curators**: Fetch curated artwork for your favorite collections.
  ![Playlist Results](docs/screenshots/entity_playlist_en.jpeg)
- **Artists & Radio**: High-resolution profile images and station covers.
  ![Artist Results](docs/screenshots/entity_artist_en.jpeg)
  ![Station Results](docs/screenshots/entity_station_en.jpeg)
- **Music Videos**: Extract frames or covers from high-quality MVs.
  ![MV Results](docs/screenshots/entity_mv_en.jpeg)

#### 📥 4. The Download Center

- **High-Quality Static Covers**: Choose between standard JPG, high-res PNG, Banner PNG, or the **Original Source** file.
- **Custom Size**: Enter custom width and height in pixels for tailored downloads.
- **4K Animated Covers**: Download motion artwork in 4K MP4 format for supported albums.

> [!TIP]
> **Timestamp Fix**: Apple Music animated covers have a 10-second timestamp offset that may cause playback issues on some players. AuralCanvas uses FFmpeg to automatically fix this. You can choose:
>
> - **Download Original MP4**: Get the raw file as-is.
> - **Download & Fix MP4 (Beta)**: FFmpeg-processed version with corrected timestamps for universal playback compatibility.

> [!TIP]
> **Recommended**: After downloading motion artwork, import it into video editing software like CapCut and re-export. This avoids compatibility issues with some players and ensures smooth playback.

- **Quick Links**: Direct URLs for easy sharing.

#### 📱 5. Mobile & Browser Recommendations

AuralCanvas is optimized for mobile devices, providing a smooth experience in your browser.

> [!TIP]
> **Recommended Browsers**: For the best experience, we recommend using **Google Chrome** or **Quark Browser**.
> **Note**: **Safari** users may encounter issues when downloading animated covers (MP4) directly due to browser limitations. Desktop Chrome/Edge is recommended for the "Fix MP4" feature.

### 🛠️ Technical Highlights

- **Hybrid Data Fetching**: Combines iTunes Search API (fast metadata) with HTML scraping (animated covers, banners).
- **Client-Side Video Processing**: Uses FFmpeg.wasm for in-browser video processing and timestamp correction.
- **Search Result Caching**: 24-hour cache for faster repeat searches.
- **Static Asset Caching**: 7-day browser caching for improved performance.
- **SEO Optimized**: Includes sitemap.xml, robots.txt, and meta tags.

---

### 💰 Maintenance & Support

Maintaining AuralCanvas incurs ongoing costs. To ensure the service remains free, we may introduce a small amount of non-intrusive advertising in the future. We appreciate your understanding!

If you find this tool helpful, consider supporting the project:

<p align="left">
  <a href="https://ko-fi.com/O5O81QNNWN" target="_blank">
    <img src="https://ko-fi.com/img/githubbutton_sm.svg" alt="在 Ko-fi 上支持我">
  </a>
</p>

---

### 🤝 Credits

Inspired by [Ben Dodson's iTunes Artwork Finder](https://github.com/bendodson/itunes-artwork-finder) project.

### 📜 License

This project is for educational and personal use only. All music artworks and related assets are copyright of **Apple Inc.** and their respective artists.

---

<a name="chinese"></a>

## 🚀 中文版

### 🌟 简介

**AuralCanvas** 是一款专为音乐爱好者和收藏者打造的轻量级网页工具。通过它，您可以轻松获取 Apple Music 上的高质量视觉资源，包括静态封面、横幅以及 4K 动态封面。

我们采用混合数据获取方式：优先使用 iTunes Search API 快速获取元数据，同时结合 HTML 抓取获取动态封面、横幅等额外资源。所有下载完全免费，无需注册。

### ✨ 核心功能

- **超高清封面**：获取最高 100000×100000 像素的超高清专辑封面。
- **动态封面**：下载 4K 动态封面视频（MP4 格式）。
- **智能搜索**：支持关键词搜索或直接粘贴 Apple Music 链接。
- **自定义尺寸**：自定义图片宽高像素，定制专属尺寸。
- **时间戳修复**：基于 FFmpeg 的动态封面时间戳自动修复，解决播放兼容性问题。
- **无需注册**：直接从 Apple Music 服务器获取资源。
- **多语言支持**：英语、中文、日语。
- **主题切换**：支持跟随系统、浅色或深色模式。

### 🌐 官方网址

- [auralcanvas.xyz](https://auralcanvas.xyz)
- [coverfetcher.xyz](https://coverfetcher.xyz)

### ⚡ 使用流程

1. **搜索** — 输入关键词或粘贴 Apple Music 链接。
2. **选择封面** — 从静态封面、横幅或动态封面中选择您需要的资源。
3. **下载高清资源** — 直接将无损、4K 分辨率的封面保存到您的设备。

### 📸 使用指南

#### 🔍 1. 主界面介绍

- **地区选择**：点击搜索框右侧的地球图标可切换 Apple Music 店面。支持地区包括：美国、英国、中国、日本、德国、法国、加拿大、澳大利亚、香港、台湾、韩国。
- **语言切换**：右上角可快速切换语言。
- **主题切换**：支持跟随系统、浅色或深色模式。

![主界面](docs/screenshots/main_interface_zh.png)

#### ⌨️ 2. 搜索与获取

- **关键词搜索**：输入专辑名、艺人或歌曲。
- **链接直接获取**：直接粘贴 Apple Music 链接（如 `https://music.apple.com/...`）。

![搜索结果](docs/screenshots/search_results_zh.png)

#### 🖼️ 3. 丰富的实体支持

无论您需要哪种类型的音乐素材，我们都能提供支持：

- **专辑与单曲**：获取高品质的方形封面。
  ![专辑搜索结果](docs/screenshots/entity_album_zh.jpeg)
- **歌单与策展人**：获取歌单配图。
  ![歌单搜索结果](docs/screenshots/entity_playlist_zh.jpeg)
- **艺人与电台**：高清的艺人背景图及电台标识。
  ![艺人搜索结果](docs/screenshots/entity_artist_zh.jpeg)
  ![电台搜索结果](docs/screenshots/entity_station_zh.jpeg)
- **音乐视频 (MV)**：提取 MV 的官方封面或关键帧。
  ![MV搜索结果](docs/screenshots/entity_mv_zh.jpeg)

#### 📥 4. 下载中心

- **高质量静态封面**：提供标准 JPG、高清 PNG、横幅 PNG 以及 **原始源文件** 下载，满足专业收藏需求。
- **自定义尺寸**：输入自定义宽高像素，定制您需要的尺寸。
- **4K 动态封面**：若该项目支持动态效果，您可以直接下载 4K 分辨率的 MP4 视频。

> [!提示]
> **时间戳修复**：Apple Music 动态封面的原始文件存在 10 秒时间戳偏移，在部分播放器上无法正确播放。AuralCanvas 使用 FFmpeg 自动修复此问题。您可以选择：
>
> - **下载原始 MP4**：获取未经处理的原始文件。
> - **下载并修复 MP4（Beta）**：经过 FFmpeg 处理时间戳修正的版本，兼容所有播放器。

> [!提示]
> **建议**：下载动态封面后，建议导入 CapCut 等视频编辑软件重新导出，可有效避免部分播放器的兼容性问题，确保流畅播放。

- **快速链接**：提供直接的图片 URL，方便分享。

#### 📱 5. 移动端与浏览器建议

AuralCanvas 在手机端拥有流畅的体验。

> [!提示]
> **浏览器建议**：为了获得最佳体验，我们建议在 iOS 和 Android 端使用 **Google Chrome** 或 **夸克浏览器**。
> **注意**：由于浏览器限制，**Safari** 用户可能无法直接下载动态封面（MP4 格式）。桌面端 Chrome/Edge 推荐使用"修复 MP4"功能。

### 🛠️ 技术亮点

- **混合数据获取**：结合 iTunes Search API（快速元数据）+ HTML 抓取（动态封面、横幅）。
- **客户端视频处理**：使用 FFmpeg.wasm 在浏览器中完成视频处理和时间戳修正。
- **搜索结果缓存**：24 小时缓存，加快重复搜索速度。
- **静态资源缓存**：7 天浏览器缓存，提升加载性能。
- **SEO 优化**：包含 sitemap.xml、robots.txt 及 meta 标签。

---

### 💰 运营与支持

维护 AuralCanvas 的正常运行需要持续的资金投入。为了确保服务能长久地提供支持，未来我们可能会在页面中加入少量非侵入式的广告。感谢您的理解！

如果您觉得这个工具有所帮助，欢迎支持我们：

<p align="left">
  <a href="https://ko-fi.com/O5O81QNNWN" target="_blank">
    <img src="https://ko-fi.com/img/githubbutton_sm.svg" alt="在 Ko-fi 上支持我">
  </a>
</p>

---

### 🤝 鸣谢

本项目受 [Ben Dodson - iTunes Artwork Finder](https://github.com/bendodson/itunes-artwork-finder) 项目启发。

### 📜 许可证

本程序仅供学习交流使用，封面版权归 Apple Inc. 及相关艺术家所有。
