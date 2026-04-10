# Naruto Rasengan Gesture Interaction Effects

一个基于 **MediaPipe Hands** 的网页互动特效项目：打开摄像头后，用户可以通过 **张开手掌蓄力 → 向前推出发射** 的手势，触发《火影忍者》风格的 **螺旋丸（Rasengan）** 视觉与音效效果。

## Demo

部署完成后可直接通过 GitHub Pages 在线体验。

- Live Demo: https://luolinjing888.github.io/naruto-rasengan-gesture-effects/

## Features

- 🌀 手掌识别与姿态追踪（MediaPipe Hands）
- ⚡ 螺旋丸蓄力、发射、命中反馈
- 🎇 粒子、光效、螺旋线、掌心发光等多层特效
- 🔊 蓄力 / 发射 / 命中音效
- 🎛️ 可调节特效大小
- 📷 浏览器端实时摄像头交互，无需后端

## How It Works

1. 允许浏览器访问摄像头
2. 保持手掌张开并稳定在画面中
3. 等待螺旋丸蓄力完成
4. 将手向摄像头方向明显推出，触发发射
5. 松手后特效会自然衰减消失

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- MediaPipe Hands
- Web Audio / HTML Audio
- Canvas 2D Rendering

## Project Structure

```text
.
├── index.html
├── assets
│   ├── rasengan-alpha.webm
│   └── sfx
│       ├── charge.mp3
│       ├── impact.mp3
│       └── launch.mp3
└── README.md
```

## Local Run

这是纯前端静态项目，直接使用本地静态服务器即可运行，例如：

```bash
python3 -m http.server 8000
```

然后打开：

```text
http://localhost:8000
```

> 提示：部分浏览器对摄像头、音频自动播放、`file://` 本地路径有权限限制，建议始终通过本地服务器或 GitHub Pages 访问。

## Browser Permissions

使用本项目时需要：

- 摄像头权限
- 浏览器支持 `getUserMedia`
- 稳定网络（用于加载 MediaPipe CDN 资源）

建议使用最新版 Chrome 或 Edge。

## Notes

- 本项目为粉丝向互动特效 Demo。
- 《Naruto / 火影忍者》相关角色与设定版权归原版权方所有。
- 本仓库仅用于创意交互展示、学习与作品集呈现。

## Suggested GitHub Description

Naruto-style Rasengan gesture interaction effect built with MediaPipe Hands, Canvas, and web audio.

## Suggested Topics

`naruto` `rasengan` `mediapipe` `gesture-recognition` `hand-tracking` `interactive-art` `creative-coding` `web-demo` `javascript` `canvas`
