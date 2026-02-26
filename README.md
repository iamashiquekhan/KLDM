<div align="center">
  <img src="ic_large_icon_kldm.webp" alt="KL Download Manager Logo" width="120"/>
  <h1>KL Download Manager (KLDM)</h1>
  <p><strong>A production-grade, ultra-fast Android Download Manager, Video Downloader & Adblock Privacy Browser built with Jetpack Compose & Material 3.</strong></p>

  <p>
    <a href="https://kldm.coinloot.in/"><img src="https://img.shields.io/badge/Official%20Website-kldm.coinloot.in-blue?style=for-the-badge" alt="Official Site" /></a>
    <a href="https://play.google.com/store/apps/details?id=com.kestlogic.kldownloadmanager"><img src="https://img.shields.io/badge/Google_Play-Download_Now-4CAF50?style=for-the-badge&logo=google-play" alt="Get it on Google Play" /></a>
  </p>
  <p>
    <img src="https://img.shields.io/badge/Platform-Android-3DDC84?style=flat-square&logo=android" alt="Android" />
    <img src="https://img.shields.io/badge/Kotlin-100%25-7F52FF?style=flat-square&logo=kotlin" alt="Kotlin" />
    <img src="https://img.shields.io/badge/UI-Jetpack%20Compose-4285F4?style=flat-square&logo=android" alt="Jetpack Compose" />
    <img src="https://img.shields.io/badge/Status-Proprietary-red?style=flat-square" alt="Proprietary App" />
  </p>
</div>

---

<p align="center">
  <b>KL Download Manager (KLDM)</b> is the ultimate all-in-one <b>video downloader</b>, <b>audio downloader</b>, and <b>fast file manager</b> app for Android. Experience lightning-fast downloads with our advanced <b>multi-thread segmented download engine</b>, and browse the web securely using our built-in <b>Privacy Browser</b> with an integrated adblocker. Designed entirely with <b>Material You (Material 3)</b>, KLDM offers an unparalleled, aesthetic, and fluid user experience optimized for seamless <b>background downloading</b>.
</p>

## ✨ Highlights & Features

| 🚀 **Fast Download Engine**                            | 🌐 **Adblock Privacy Browser**                         |
| ---------------------------------------------------- | ---------------------------------------------------- |
| • **Multi-threaded & Segmented Downloads**           | • Built-in **Adblock Engine** & popup blocker        |
| • Smart URL sniffing & auto-capturing                | • **Resource Detection Pipeline** (video/audio sniff)|
| • Pause, Resume, and Auto-retry capabilities         | • Advanced **Tab Management** & Session Restore      |
| • Background downloading via Foreground Services     | • Incognito mode with strict privacy enforcement     |
| • Concurrent download limits & Global speed control  | • Per-host site settings (JS, Desktop mode, Dark mode)|

| 📁 **Smart File Manager & Video Downloader**           | 🎨 **Premium UI & Architecture**                       |
| ---------------------------------------------------- | ---------------------------------------------------- |
| • **Media Detector:** Auto-find videos on any page   | • Ultra-smooth **Jetpack Compose** interface         |
| • **Audio Downloader:** Save music tracks easily     | • Beautiful **Material 3 / You** dynamic theming     |
| • Easy file categorization & secure storage          | • **Offline-first** Room DB persistent storage       |
| • Clipboard monitoring & auto-capturing              | • Edge-to-Edge display with elegant animations       |

## 📱 Screenshots

<div align="center">
  <img src="IMG_KLDM_SS.webp" width="30%" alt="Downloads Notifications">
  &nbsp;&nbsp;
  <img src="IMG_KLDM_BROWSER.webp" width="30%" alt="Advanced Browser">
  &nbsp;&nbsp;
  <img src="IMG_KLDM_VIDEO DOWNLOADER.webp" width="30%" alt="Video Downloader">
</div>

*Note: Screenshots above feature the dynamic Material You theming and edge-to-edge UI spanning the entire system.*

## 🛠️ Technology Stack

Built with modern Android development practices to ensure high performance, maintainability, and scalability.

- **Language:** [Kotlin](https://kotlinlang.org/)
- **UI Framework:** [Jetpack Compose](https://developer.android.com/jetpack/compose) with Material 3 Design
- **Architecture:** Clean Architecture + MVVM + MVI Concepts
- **Dependency Injection:** [Hilt](https://dagger.dev/hilt/)
- **Database / Persistence:** [Room](https://developer.android.com/training/data-storage/room) & [DataStore](https://developer.android.com/topic/libraries/architecture/datastore)
- **Networking:** [OkHttp](https://square.github.io/okhttp/) (Custom segmented download engine architecture)
- **Asynchronous Processing:** Kotlin Coroutines & Flows
- **Background Tasks:** Android WorkManager & Foreground Services

## 🚀 Download & Installation

KL Download Manager is a proprietary, closed-source application designed to provide the best downloading & file management experience on Android.

You can download the official release from:

- 🌐 **[Official Website](https://kldm.coinloot.in/)**
- 📱 **[Google Play Store](https://play.google.com/store/apps/details?id=com.kestlogic.kldownloadmanager)**

*Note: This is not an open-source project. The source code and repository are private.*

## 🛡️ Play Policy & Security Compliance

KL Download Manager takes user safety and Google Play Store policies strictly:
- ✅ **No YouTube Downloads:** Strictly blocks YouTube URLs to comply with terms of service.
- ✅ **Privacy First:** Explicit permissions asked only when required, no unauthorized tracking.
- ✅ **Secure Browsing:** The built-in browser isolates incognito sessions and blocks intrusive ads.
- ✅ **No DRM Bypass:** KLDM respects copyright and avoids downloading protected content.

## 🗺️ Roadmap & Project Status

KLDM is built iteratively in phases. Some of our major milestones:
- [x] **Phase 1-2:** Clean Architecture Setup & Core Single-stream HTTP Downloader.
- [x] **Phase 3:** Multi-threaded Segmented Downloading & Speed Limits.
- [x] **Phase 4-5:** Privacy Browser integration & Core Resource Sniffer.
- [x] **Phase 6-7:** Application Polish, SAF integration, and Clipboard Monitoring.
- [x] **Phase 8-9:** Resource Detection Pipeline, Media Preview, Browser Productivity Pack (Host Settings).
- [ ] **Phase 10:** Final Polish, Performance Optimizations & Google Play Store release preparations.

## 📁 Project Structure

```text
KL-Download-Manager/
├── app/                  # Main Compose UI, Navigation, ViewModels, Theme
├── browser-core/         # Privacy Browser engine, Adblocker, Resource Sniffing
├── common/               # Shared domain models, utilities, and constants
├── data/                 # Room Database entities & DAOs, DataStore Preferences
├── download-core/        # Multi-Threaded HTTP engine, Segment merging, Services
└── media-core/           # Video and audio detection, parsing, and processing
```

## 📜 License

Copyright © 2026 KestLogic Solutions. All rights reserved.

---
<div align="center">
  <sub>Developed with ❤️ by KestLogic. Optimizing the way you download on Android.</sub>
</div>


