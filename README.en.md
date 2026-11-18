# Kingfisher Tracking Trainer

[日本語](README.md)

A joke web app for practicing your tracking on a kingfisher that flies and dives, from in front of a monitor at home.

**Try it:** https://meinogizaka.github.io/KingfisherTrackingTrainer/

Enter the monitor size, where you stand, and the lens focal lengths. The kingfisher on screen then approaches the apparent size and speed you would see through the viewfinder in those conditions. It is a rehearsal before you head to the river. Exposure and focus are outside this bird's duties.

The labels on the page are Japanese. For the app itself, use your browser's translate feature.

## What you see

Ten dive points sit on the water, and five perches stand above it. The kingfisher waits on a branch, turns its face and beak toward the landing spot, crouches, and then takes off. After it hits the water it dips under for a moment and comes back up to a perch. At the probability you set, it returns to the perch it dived from.

Sometimes it crouches and then stays where it is. That is a feint.

There are three flight paths.

- Perches and dives (止まり木＋ダイブ)
- Level flight (水平飛行)
- Undulating flight (上下飛行)

The background can be a riverside or a plain field.

## How to match your setup

1. Enter the width of the picture actually shown on the monitor, in centimeters.
2. Enter the distance from your eye to the monitor.
3. Enter the focal length of the lens you use in the field, and of the practice lens you are looking through now, as 35mm-equivalent millimeters.
4. Enter the distance you have in mind for the kingfisher, its flight speed, and its body length.
5. Press 開始 / 再スタート (Start / Restart) and switch to full screen.
6. Step back by the distance you entered, and track the bird through the practice lens.

Turn on the 20 cm 基準線 (20 cm reference line), measure it with a ruler, and type that length into 基準線の実測値 (measured length of the reference line). The scale on screen then matches what you measured.

The panel shows the estimated angular speed, the share of the field lens frame the bird occupies horizontally and vertically, and the kingfisher's length on the monitor.

Settings are stored in the browser. 設定値を初期化 (Reset to defaults) restores the original values.

## Controls

| Control | Action |
| --- | --- |
| Space | Pause / resume |
| R | Restart |
| F | Full screen |
| 設定を隠す (Hide settings) | Close the panel at the top left |

## Open it locally

Open [index.html](index.html) in a browser. [kingfisher_tracking_trainer.html](kingfisher_tracking_trainer.html) is the same file. Nothing needs to be built.

## License

[MIT License](LICENSE)

Copyright (c) 2026 [MeiNogizaka](https://x.com/MeiNogizaka)
