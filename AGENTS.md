# Agent Instructions for kamil_Rblog

This repository contains the source code for Kamil Sijko's personal website and blog, built with Hugo (extended edition) and the [Blowfish](https://blowfish.page/) theme.

## General Guidelines

- **Multilingual Content**: Most content has Polish (`index.md`) and English (`index.en.md`) versions. Ensure any new content or changes maintain parity between both languages.
- **Verification**: Always verify site builds using `hugo --gc --minify` before completing tasks.

## Photography Section (`content/fotografia/`)

When adding or modifying photo essays and travel posts:

1. **Page Bundles**:
   - Organize each post as a page bundle: `content/fotografia/YYYY-MM-DD-<slug>/` containing `index.md`, `index.en.md`, and image assets.
   - Lead image should be named `featured.webp` (or `featured.jpg`), which Blowfish automatically detects as the card thumbnail and Open Graph preview.

2. **Image Conversion**:
   - Always convert images to WebP in **100% full original resolution** preserving all EXIF and color profile metadata:
     ```shell
     cwebp -q 92 -m 6 -metadata all input.jpg -o output.webp
     ```

3. **Gallery & Image Zoom (CRITICAL)**:
   - When using the `{{< gallery >}}` shortcode, **ALWAYS** provide both `src` and `data-zoom-src` on every `<img>` tag:
     ```html
     {{< gallery >}}
       <img src="featured.webp" data-zoom-src="featured.webp" class="grid-w100" alt="Opis zdjęcia" />
       <img src="zdjecie-1.webp" data-zoom-src="zdjecie-1.webp" class="grid-w100 sm:grid-w50" alt="Opis zdjęcia 1" />
       <img src="zdjecie-2.webp" data-zoom-src="zdjecie-2.webp" class="grid-w100 sm:grid-w50" alt="Opis zdjęcia 2" />
     {{< /gallery >}}
     ```
   - **Why this is required**: Without `data-zoom-src`, Blowfish's `medium-zoom` library zooms the thumbnail resolution rendered on the grid instead of displaying the full-resolution image.
   - Use Blowfish grid classes (`grid-w100`, `grid-w100 sm:grid-w50`, `grid-w33`, etc.) to control responsive layout in the gallery.
