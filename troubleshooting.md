---
layout: default
title: Troubleshooting
nav_order: 6
---

# Troubleshooting

## No videos appear

Confirm videos are directly inside the selected folder. BRV does not scan subfolders and only lists supported extensions.

## The resize button is unavailable

Choose an input folder with at least one video, set a separate output folder, and use even width and height values between 64 and 7680 pixels.

## My frame has black bars

Black bars are expected with **Fit within** when the source and target aspect ratios differ. Use **Crop to fill** if the output must fill the entire target frame.

## The important subject is cropped

With **Crop to fill**, choose the focus anchor closest to the content that must remain visible. Use the frame preview and test a short representative clip before a large batch.

## A file fails

Try another source video first. A common extension can still contain damaged or uncommon streams that FFmpeg cannot decode. Check that the output folder is writable and has enough free space.
