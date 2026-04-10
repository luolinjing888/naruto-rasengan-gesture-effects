# Naruto Rasengan Gesture Interaction Effects

A browser-based interactive effect inspired by **Naruto**, built with **MediaPipe Hands**. After enabling the camera, users can **open their palm to charge** and then **push forward or point a finger-gun gesture at the camera** to trigger a **Rasengan-style visual and sound effect**.

## Demo

Try it online via GitHub Pages:

- Live Demo: https://luolinjing888.github.io/naruto-rasengan-gesture-effects/

## Features

- 🌀 Real-time hand tracking with MediaPipe Hands
- ⚡ Rasengan charging, launching, and impact feedback
- 🎇 Multi-layer visual effects including particles, glow, spiral lines, and palm lighting
- 🔊 Charge / launch / impact sound effects
- 🎛️ Adjustable effect size
- 📷 Fully client-side camera interaction with no backend required

## How It Works

1. Allow browser access to your camera
2. Hold an open palm steadily in view to begin charging
3. Wait until the Rasengan is fully charged
4. Push your hand forward or point a finger-gun gesture toward the camera to launch it
5. Release or relax the gesture to let the chakra effect fade out naturally

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- MediaPipe Hands
- HTML Audio
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

## Run Locally

This is a static front-end project, so you can run it with any simple local server. For example:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

> Note: Some browsers restrict camera access, autoplay audio, or `file://` behavior. It is recommended to run the project through a local server or GitHub Pages instead of opening the file directly.

## Browser Requirements

To use this project, your browser should support:

- Camera permission access
- `getUserMedia`
- A stable network connection to load MediaPipe assets from CDN

For the best experience, use the latest version of Chrome or Edge.

## Notes

- This project is a fan-made interactive demo.
- Naruto and related characters, names, and concepts belong to their respective copyright holders.
- This repository is intended for creative coding, learning, and portfolio presentation.

## GitHub Description

Naruto-style Rasengan gesture interaction effect built with MediaPipe Hands, Canvas, and web audio.

## Suggested Topics

`naruto` `rasengan` `mediapipe` `gesture-recognition` `hand-tracking` `interactive-art` `creative-coding` `web-demo` `javascript` `canvas`
