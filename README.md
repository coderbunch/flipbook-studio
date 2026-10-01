# FlipBook Studio 📖✨

> **3D Virtual Flipbook Generator for Windows.**  
> Transform raw text, Markdown articles, multi-page PDFs, and photo albums into interactive 3D virtual flipbooks with authentic paper physics, synthesized rustle sound, and zero-dependency web exports.

[![Official Product Page](https://img.shields.io/badge/Coderbunch-Official_Product_Page-123b32?style=for-the-badge&logo=googlechrome)](https://coderbunch.com/apps/flipbook-studio/)
[![Download Setup (.exe)](https://img.shields.io/badge/Download-Windows_Setup_v1.0.0-2a6b5a?style=for-the-badge&logo=windows)](https://coderbunch.com/downloads/FlipBook-Studio-1.0.0-Setup.exe)
[![GitHub Release](https://img.shields.io/badge/GitHub-v1.0.0_Release-181717?style=for-the-badge&logo=github)](https://github.com/coderbunch/flipbook-studio/releases/tag/v1.0.0)
[![Report an Issue](https://img.shields.io/badge/Feedback-Open_an_Issue-e06c75?style=for-the-badge&logo=github)](https://github.com/coderbunch/flipbook-studio/issues)

---

## 📥 Downloads

| File | Type | Architecture | Size | Direct Download |
| :--- | :--- | :--- | :--- | :--- |
| **`FlipBook-Studio-1.0.0-Setup.exe`** | Windows Installer | Windows 10 / 11 (64-bit) | ~1.35 MB | [**Download via Coderbunch CDN**](https://coderbunch.com/downloads/FlipBook-Studio-1.0.0-Setup.exe)<br>[**Download via GitHub Release**](https://github.com/coderbunch/flipbook-studio/releases/download/v1.0.0/FlipBook-Studio-1.0.0-Setup.exe) |

*The installer includes desktop and start-menu shortcuts and a clean uninstaller. No account, sign-in, or subscription required.*

---

## 🌟 Key Features

### 1. Smart Text & Markdown Typesetting
- Paste plain text or Markdown manuscripts and let the engine calculate typographic heights and word-wraps across spreads.
- **Ornate Cover Generator**: Creates decorative front and back covers with custom titles, author bylines, and ornamental borders.
- **4 Curated Reading Themes**:
  - **Warm Paper**: Classic literary beige background with Georgia serif and traditional drop-caps.
  - **Editorial Serif**: Ivory paper with crisp editorial margins tailored for reports and magazines.
  - **Modern Minimal**: Clean white backdrop with sleek sans-serif typography for technical manuals.
  - **Night Owl**: Low-strain dark slate contrast designed for comfortable nighttime reading.

### 2. High-Resolution PDF Ingestion
- Drag and drop any multi-page PDF document (catalogs, brochures, magazines, manuscripts).
- Built-in offline PDF parser with selectable rendering densities (1.2× draft, 1.6× balanced, 2.0× ultra-HD retina).
- Preserves original page aspect ratios and generates interactive navigation thumbnail filmstrips.

### 3. Realistic 3D Canvas Physics & Web Audio
- Smooth page-turning curvature with dynamic bend meshes, light gradients, and drop shadows.
- **Synthesized Paper Sound**: Generates authentic paper rustle audio in real-time via the Web Audio API with zero external audio assets or downloads.
- Interactive controls: drag page corners, mouse wheel zoom, keyboard arrows, and auto-flip autoplay.

### 4. Zero-Dependency Web & Offline Export
- **Standalone Web Package (`.zip`)**:
  - Exports a clean, self-contained static website (`index.html`, `flipbook.js`, `flipbook.css`, page images).
  - Unzip and upload to Apache, Nginx, Netlify, Cloudflare Pages, GitHub Pages, or AWS S3.
- **Single-File Offline HTML (`.html`)**:
  - Packs the entire publication and viewer into a single `.html` file. Double-click to open and read in any browser completely offline.
- **Responsive Embed Code**:
  - One-click copy of responsive `<iframe>` code snippets ready for WordPress, Shopify, Webflow, or Squarespace.

### 5. 100% Offline & Private
- All processing, PDF rasterization, text typesetting, and file packaging run locally on your workstation.
- Your manuscripts and private catalogs never touch external cloud servers.

---

## 📖 User Guide & Documentation

### Ingesting Content
1. **PDFs**: Click **Import PDF** or drag and drop any PDF file. FlipBook Studio renders each page and displays thumbnails in the manager filmstrip.
2. **Text / Markdown**: Switch to the **Raw Text / Markdown** tab, paste your article or book chapters, and select a theme. Use standard Markdown headings (`# Chapter 1`) to generate chapter marks in the Table of Contents.
3. **Image Portfolios**: Import sequential JPG, PNG, or WebP files to create photo lookbooks or comic albums.

### Customizing the Viewer
- Adjust the page-turn duration (from 400ms brisk to 1200ms slow novel-turn).
- Choose your reader desk background: Mahogany Wood, Midnight Slate, Clean Studio, or Warm Cream.
- Toggle sound effects on or off and calibrate volume.

### Embedding on Your Website
After exporting the **Web Package (.zip)**, upload the extracted folder to your web host (e.g. `https://yourwebsite.com/catalog/`). Then insert the following responsive embed code into your page:

```html
<!-- Responsive FlipBook Embed -->
<div style="position: relative; padding-bottom: 65%; height: 0; overflow: hidden; max-width: 100%;">
  <iframe src="https://yourwebsite.com/catalog/" 
          style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: 0;" 
          allowfullscreen></iframe>
</div>
```

### Keyboard Shortcuts
| Key | Action |
| :--- | :--- |
| **Left Arrow** / **Right Arrow** | Turn to Previous / Next page spread |
| **Spacebar** | Play / Pause auto-flip presentation mode |
| **F** | Toggle Fullscreen reading mode |
| **+** / **-** | Zoom In / Zoom Out |
| **0** | Reset zoom to default |
| **Escape** | Close modal dialogs / Exit zoom mode |

---

## 💻 System Requirements

- **Operating System**: Windows 10 (1809+) or Windows 11 (64-bit).
- **Runtime**: Powered by native Windows WebView2 (pre-installed on Windows 10/11).
- **RAM**: Minimum 4 GB (8 GB recommended for large 500+ page documents).
- **Disk Space**: 15 MB free disk space for installation.
- **Internet**: Not required — works 100% offline.

---

## 🐛 Issues, Bug Reports & Feature Requests

Encountered an issue or have a feature suggestion?
- **Create an Issue**: [**GitHub Issues Tracker**](https://github.com/coderbunch/flipbook-studio/issues)
- Please include:
  1. Your Windows OS version (e.g., Windows 11 23H2).
  2. Steps to reproduce the problem.
  3. Format of the file imported (PDF, TXT, MD, or images).
  4. Any error messages or screenshots.

---

## 📬 Contact & Support

- **Email Support**: [hello@pinetechits.com](mailto:hello@pinetechits.com)
- **Official Website**: [coderbunch.com/apps/flipbook-studio/](https://coderbunch.com/apps/flipbook-studio/)
- **Publisher**: **PINETECH IT SOLUTIONS PRIVATE LIMITED** (India)

---

## ⚖️ License

FlipBook Studio is published by Pinetech IT Solutions Private Limited under the Coderbunch brand. Users retain 100% ownership and copyright of all manuscripts, publications, graphics, and web packages generated using the software, with royalty-free commercial distribution rights. See [Terms of Use](https://coderbunch.com/apps/flipbook-studio/terms/) and [Privacy Policy](https://coderbunch.com/apps/flipbook-studio/privacy/) for details.
