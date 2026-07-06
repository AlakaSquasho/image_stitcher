# Image Stitcher

A lightweight single-file image stitching tool that runs directly in the browser. No build step, dependency installation, or local server is required.

[中文说明 / Chinese README](./README_zh.md)

## Features

- Supports horizontal, vertical, 2x2, and 3x3 image layouts
- Lets you customize the image count for horizontal and vertical layouts
- Supports drag and drop, click-to-select, and paste-from-clipboard image import
- Automatically fills available slots and crops images to fit each cell on export
- Lets you adjust the canvas preview zoom level
- Supports image borders with configurable color and width
- Exports to PNG, JPG, and WEBP
- Includes light and dark theme modes
- Includes keyboard shortcuts for export and theme toggle

## Usage

1. Open `index.html` in your browser
2. Choose a layout from the left sidebar
3. Drag images into the canvas, or click a slot to select files
4. Adjust image count, zoom, border settings, and export format in the right toolbar
5. Click **Export Image** to save the result

## Interaction Notes

- Horizontal / vertical layouts support custom image counts
- 2x2 layout uses exactly 4 images
- 3x3 layout uses exactly 9 images
- You can paste an image from the clipboard into the next available empty slot
- Keyboard shortcuts:
  - `Ctrl/Cmd + E`: export image
  - `Ctrl/Cmd + D`: toggle theme

## Project Structure

```text
.
├── index.html
├── README.md
└── README_zh.md
```

This is intentionally a single-HTML-file project, with HTML, CSS, and JavaScript kept inline for easy sharing and direct browser use.

## Good Fit For

- Quickly stitching multiple images into one long image or grid
- Making simple comparison sheets, screenshot collections, or 3x3 collages
- Using a local tool without introducing a build system
