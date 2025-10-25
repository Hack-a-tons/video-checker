# Video Checker

> **Note:** This project was abandoned in favor of a different idea for the hackathon. The repository contains only the Skip framework skeleton and planning documents (see TODO.md). Feel free to use this as a starting point if you want to implement the concept.

## Project Description
Real-time "reality overlay" for any video. Select a video from your library, and the app auto-extracts narration, splits it into factual claims, and sync-scrolls them beside the video for live truth awareness.

## Hackathon Context
This project has been built for the [**$5000 De-Vibed Hackathon**](https://luma.com/dj3k3tri) — hosted at AngelList Founders Cafe, San Francisco — taking place October 24–25, 2025. The event focuses on building real AI software without "AI slop", with surprise feature challenges revealed mid-way.

## Vision
Video-checker enhances how people consume viral video content by revealing the factual layer behind it in real time. Users can load any video directly from their phone's local library — it appears and plays in the video window. Meanwhile it is also uploaded to the server, processed, and processed text begins to appear in the text window with synchronized claim awareness.

## Features
- Real-time transcription placeholder
- Two-pane UI: video + fact intelligence stream
- Scroll-sync in both directions
- Designed for Skip cross-platform (iOS + Android)

## Development / Running the App
Xcode and Android Studio must be installed.

An **Android emulator must already be running** (launch from Android Studio → Device Manager).

From the project root, run:
```bash
open Darwin/VideoChecker.xcodeproj
```
This opens Xcode.

To run the app on both platforms simultaneously:
- Select the **VideoChecker** target in Xcode
- Press **Run** — this launches the iOS simulator
- A build phase will automatically run the **“Launch Android APK”** script, deploying the transpiled Android app to the running Android emulator or connected device.

**Logs**
- iOS logs appear in **Xcode console**
- Android logs appear in **Android Studio → Logcat tab**

