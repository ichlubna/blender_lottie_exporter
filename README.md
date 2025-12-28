# Blender Lottie Exporter

Supports exporting Grease Pencil as Lottie:
- `Export > Grease Pencil as Lottie(.json)`

## Install

1. Click Code icon > Download ZIP
2. Open Blender Preferences > Get Extensions > Install from Disk > select the downloaded zip file of this repo.
2. In this addons preferences, click `Install` to install scour package( required if `optimize_svg` is enabled when exporting )

## How it works

This addon renders grease pencil animation to SVG frame by frame, then embeds each frame into the Lottie image layer. Animation is played by changing the visibility of each image layer.
