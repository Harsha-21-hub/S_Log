# 📓 S Log

S Log is a lightweight, high-performance daily habit tracker and streak manager for Android 12+. Designed as part of the "S Suite" ecosystem, it features a custom "Nothing OS" inspired dot-matrix aesthetic and a smart, time-based notification engine to provide a seamless, focused workspace for building consistent daily routines.

## ✨ Features

* **Smart Streak Engine:** Built with custom tracking logic that rewards consistency and accurately maintains both current and maximum streaks.
* **Dynamic Time-Based Scheduling:** Automatically schedules local reminders based on your preferred study blocks (Morning, Afternoon, Evening, Night) to help you stay on track throughout the day.
* **Nothing-Inspired Aesthetics:** Features a custom monochrome themed icon and dot-matrix visual identity that perfectly aligns with modern Android 13+ theming.
* **Persistent State:** Automatically stores your habits, streaks, and schedules locally so you never lose your progress between sessions.
* **Privacy First:** S Log operates entirely offline and locally. It does not collect, transmit, or sell any personal user data.

## 🚀 How to Install

1. Go to the **Releases** section on the right side of this repository.
2. Download the latest `S_Log.apk` file to your Android device.
3. Open the file and tap **Install** (you may need to allow "Install from Unknown Sources" in your browser or file manager settings).

## 🔒 Permissions Guide

S Log uses notifications to keep your habits and reminders synchronized locally.

### 1. Notifications Permission

* **Why it's needed:** To deliver scheduled reminders for your study blocks and help maintain daily consistency.
* **How to grant:** When prompted upon launching the app, allow notification permissions to ensure reminders function correctly.

## 🛠️ Technical Specs

* **Minimum SDK:** Android 12 (API Level 31)
* **Architecture:** MVVM with Jetpack Compose
* **Package:** `com.hesi.slog`
* **Language:** Kotlin
* **Database:** Room (Local-only storage)
* **Background Tasks:** WorkManager (Time-based scheduling)
