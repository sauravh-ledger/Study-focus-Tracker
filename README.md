# Study Focus Tracker

A webcam-based study companion that measures **real focus time**. It runs entirely in the browser using on-device AI — no video is saved or uploaded.

**Live app:** https://sauravh-ledger.github.io/Study-focus-Tracker/

## Features

- **Focus detection** – classifies each moment as *studying*, *on phone*, or *away* using MediaPipe object detection (person + cell phone).
- **Voice warnings** – spoken reminders in English or Hindi when you use your phone too long.
- **Red alert** – full-screen flashing alert with an alarm if you keep using your phone.
- **Mood helper** – reads facial expression (smile / frown) with MediaPipe Face Landmarker:
  - looks sad → 1-minute relax break with calm generated music and a breathing guide
  - smiling → confetti, a happy tune, and one of your own saved happy moments
- **Pop quizzes** – a quick question every few focused minutes; add your own questions too.
- **Pomodoro breaks** – a break reminder after every 25 minutes of real focus.
- **Session report & 7-day chart** – focus score, phone warnings, quiz score, mood moments, and a study streak.
- **Demo mode** – buttons to try every feature without a camera.

## How to use

1. Open the live link in Chrome or Edge (laptop or phone).
2. Click **Start Study Session** and allow camera access.
3. Sit so your face and desk are visible. Click **End & see report** when done.

You can also download `index.html` and open it directly in Chrome. An internet connection is needed to load the AI models.

## Tech

HTML, CSS, JavaScript · [MediaPipe Tasks Vision](https://ai.google.dev/edge/mediapipe) (EfficientDet-Lite0, Face Landmarker) · Web Speech API · Web Audio API

## Privacy

All AI runs locally in the browser. Camera frames never leave the device. Settings and history are stored only in your browser.

## Author

Sauravh Yadav — first-semester CSE student, EDI project (2026).
