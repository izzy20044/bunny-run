# 🐰 Bunny Run

A tiny 2D endless runner. You're a bunny. Logs happen. Jump them.

**▶ Play in your browser: https://izzy20044.github.io/bunny-run/**

![screenshot](https://izzy20044.github.io/bunny-run/screenshot.png)

## How to play

| Input | Action |
|---|---|
| **Space** / **Up arrow** | Jump |
| **Tap** (mobile) | Jump |
| **Space / Tap** after a crash | Restart |
| **Esc** | Reset best score |

- Score climbs the further you run.
- The game gets faster the longer you survive (speed 5 → 16).
- As speed rises, gravity rises too — same jump height, quicker landings — so you can react to tighter log spacing.
- The run only ends when you hit a log. Best score is saved in your browser.

## Windows version

A standalone desktop build (`BunnyRun.exe`, no install needed) is on the
[Releases page](https://github.com/izzy20044/bunny-run/releases).

## Tech

- Single-file HTML5 canvas game — no dependencies, no build step.
- All art (pixel bunny, logs, sky, clouds) is drawn in code.
- The desktop version is the same game written in Python + pygame, packaged with PyInstaller.

Made with Claude 🤖
