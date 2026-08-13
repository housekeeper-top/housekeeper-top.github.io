---
title: Hacker Camera
author: Jane. R
date: 2026-8-12
category: hackercamera
layout: post
---

Hacker Camera is a camera with a live telemetry head-up display. A stream of green readouts runs down the viewfinder, refreshing one line at a time, and everything you enable gets burned into the photo or video you capture.

**Viewfinder.** A terminal-style HUD with corner brackets, a crosshair, scanlines and monospaced readouts. The data stream refreshes line by line; tap it for an instant full sweep. Tap to focus, long press to lock AE/AF, pinch to zoom. Lens stops are read from the actual hardware, so supported models expose 0.5x, 1x and 3x as real optical steps rather than digital crops.

**Capture.** Full-resolution photos with quality prioritization, and video with audio, stabilization and a live timecode. The data lines are drawn into the photo itself and composited into the video during export. GPS is written to EXIF and QuickTime metadata: coordinates, altitude, speed and heading.

**Telemetry, grouped and optional.** Everything is off by default except the app tag, the clock and the exposure readout. You turn on only what you want, and a permission is requested only at the moment you enable a field that needs it.

* System — device, OS, battery, thermal state
* Exposure — ISO, shutter, aperture, EV, zoom
* Time — clock, date, time zone
* Location — coordinates, place name, altitude, speed, heading
* Environment — weather, temperature, UV index, barometric pressure, magnetic field, light level, ambient noise
* Body — steps, heart rate, blood oxygen, HRV, body temperature
* Network — link type, Wi-Fi name, nearby Bluetooth LE device count

**Archive.** Browse, view and play back your captures inside the app. Swipe up to mark for deletion, swipe down to go back, swipe sideways to browse, then delete everything you marked in one pass.

**Honest about limits.** iPhone has no UV, ambient light or chassis temperature sensor, and iOS does not expose cellular signal strength or the list of nearby Wi-Fi networks. Where a reading cannot come from hardware, the app says so in the settings screen and shows the closest real equivalent instead: UV and weather from a public meteorological service, light level computed from the live exposure triangle, thermal level instead of a temperature, and link type instead of dBm.

Nothing is tracked, and nothing leaves your device except the coordinates needed to fetch weather when you turn that field on.

**Free and Pro.** The app is free. Without a subscription the data stream is fixed to three readouts — app tag, GPS coordinates and clock. Hacker Camera Pro unlocks the full field list, the per-group switches and the burn-in layout, as a monthly or yearly auto-renewing subscription. Prices are shown in the app in your local currency before you confirm, and the subscription works on every device signed in with your Apple Account. If it lapses, the app keeps working as the free version and your selection is kept for when you come back.

* [Privacy Policy](/hackercamera/privacy/en/) · [隐私政策](/hackercamera/privacy/zh/)
* [User Terms](/hackercamera/user_terms/en/) · [用户协议](/hackercamera/user_terms/zh/)
