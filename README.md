# HoloCube GS for Mac

Light-field digital human for the Mac. Plug in a **DIY1** (1440×1440) or **C1** (1440×2560) light-field display, then chat with the character or use it as a live interpreter. Same engine as the iOS app.

**Download:** [latest notarized DMG](https://github.com/sintlab/holocube-gs-mac/releases/latest) · install guide & release history: **https://holo.sintlab.com/mac/**

## Requirements

- Apple Silicon Mac (M1 or later)
- macOS 15 or later — macOS 26 recommended (WebGPU on by default)
- About 1 GB of disk space
- A microphone (built-in or external) and a DIY1 / C1 display; other displays are left alone

## Install

1. Open the DMG and drag **HoloCube GS** into **Applications**.
2. Launch it. The app is signed with Developer ID and notarized by Apple, so it opens with a normal double-click.
3. Allow microphone access when asked.
4. First time only: paste the connection address you were given into **Settings › Connection** and click **Apply**.

## Update

1. Quit the running app (⌘Q).
2. Drag the new version into **Applications** and choose **Replace** (not "Keep Both").

Your connection token, display choice and panel settings are kept — no need to paste the address again.

## Latest: 1.0 (202610210348)

- Microphone audio is now compressed (Opus, about 30 kbps instead of 256 kbps). Fixes calls dropping with *"云端识别不可用 … Operation canceled"* on slow or long-distance connections (e.g. New Zealand → China).
- Clearer message when the connection drops, plus a warning when the network can't keep up.

---

This repository only hosts release binaries.
