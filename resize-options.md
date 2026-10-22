---
layout: default
title: Resize Options
nav_order: 3
---

# Resize Options

## Output size and presets

Enter a custom width and height, or start with a built-in preset. Social-media choices include Instagram portrait (1080 × 1350), Instagram square (1080 × 1080), TikTok / Reels (1080 × 1920), YouTube (1920 × 1080), YouTube Short (1080 × 1920), and Facebook landscape (1280 × 720). Common video-size choices include 4K UHD (3840 × 2160), Full HD (1920 × 1080), HD 720p (1280 × 720), SD 480p (854 × 480), and VGA (640 × 480).

Selecting a preset updates both size fields and highlights that choice. Editing either dimension returns the controls to a custom size.

Use even dimensions. H.264 video with the compatible `yuv420p` pixel format requires even width and height values.

## Frame fitting

- **Fit within** preserves the complete original frame. If its aspect ratio differs from the target, BRV adds black bars to make the exact output size.
- **Crop to fill** fills the target frame without bars. It crops the surplus from the original frame.

## Crop focus

Crop to fill offers nine focus anchors: each corner, the top, bottom, left, right, and centre. Choose the area that should stay visible in every video. For example, use **Top** for a presenter near the top of portrait footage, or **Centre** for a balanced crop.

## Frame preview

BRV extracts a real frame from the first supported video in the folder and renders it using the current resize settings. Compare **Original**, **Resized**, or **Split** before starting. A preview represents its sample frame; review a short output when the folder contains mixed orientations or different compositions.

## Encoding

Use CRF 23 as a balanced starting point. Lower values preserve more detail and usually create larger files. **Slow** may reduce size at the same quality, while **Fast** finishes sooner. Choose 128, 192, or 256 kbps AAC audio according to the delivery needs.
