---
layout: default
title: Output and Safety
nav_order: 5
---

# Output and Safety

BRV starts with a separate `resized` output folder inside the selected input folder. Choose **Browse** to select another destination or type an absolute folder path.

The default suffix is `_resized`, so `clip.mov` becomes `clip_resized.mp4`. Change or clear it to suit your workflow.

For every input, BRV writes a temporary MP4 candidate in the output folder. It promotes that candidate only after FFmpeg succeeds and it has a non-zero size. Original videos are never overwritten.

Enable **Skip existing output files** to preserve a prior output during a re-run. With it off, a successfully completed resized copy replaces an existing output with the same name.
