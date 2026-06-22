# EditCall Log - Organize Your Call History

![Build APK](https://github.com/Mudit-pip/EditCall-Log/actions/workflows/build-apk.yml/badge.svg)

EditCall Log: An **Android application** designed to help you **manage your call logs effectively**. It allows you to add new call entries with customizable details, providing a convenient way to organize your call history.

## Features

- **Add New Calls:** Effortlessly create new entries for missed calls, outgoing calls, or incoming calls.
- **Detailed Customization:** Specify the date, time, contact information (number or name), and duration of the call.
- **Intuitive Interface:** Material Design clock face and calendar pickers for smooth date/time selection.
- **24-Hour Time Format:** Time picker uses 24-hour format with an analog clock face dial.
- **Second-Level Duration:** Set call duration with both minutes and seconds precision.
- **Clock Face Duration Picker:** Duration selector uses an analog clock dial starting at 00:00 (12 o'clock), with ±15m quick-adjust buttons for longer calls.
- **Clipboard Paste:** Tap the phone icon to paste a number directly from clipboard.
- **Quick-Action Icons:** Each row has a quick-action icon on the left:
  - 📅 Tap date icon → set to today
  - ⏰ Tap time icon → set to current time
  - 📞 Tap phone icon → paste from clipboard
  - 🔢 Tap duration icon → randomize seconds
- **"Now" Button:** Time picker includes a "Now" button to instantly set the current time.
- **Default Current Time:** Time picker defaults to the current time on first open.
- **Random Seconds:** Duration picker has a "Rand sec" button for random second values.
- **GitHub Actions Build:** Automated APK build on every push — published to Releases as "Latest Build".

## What's New

- **⏱ Second-level Duration:** Set call duration with both minutes and seconds precision (e.g., "3 min 45 sec").
- **🕐 Clock Face Pickers:** Time and duration selection now use analog clock dials instead of scroll wheels.
- **📅 Calendar Picker:** Date selection uses the Material calendar view for a more intuitive experience.
- **📋 Clipboard Paste:** Tap the phone icon to paste a number from clipboard.
- **🔢 Random Seconds:** Tap the duration icon for random seconds, or use the "Rand sec" button in the picker.
- **⏰ Quick Time:** Tap the time icon or use the "Now" button to set current time instantly.
- **📅 Quick Date:** Tap the date icon to set today's date.
- **🤖 Automated Builds:** APK is automatically built via GitHub Actions and published to Releases on every push.

## Screenshots

<p float="left">
  <img src="https://github.com/Mudit-pip/EditCall-Log/assets/70972592/c09b1289-4246-4579-8475-a628a5f7d6ff" width="30%" />
  <img src="https://github.com/Mudit-pip/EditCall-Log/assets/70972592/371c7172-0d7c-4117-aaf0-e0ba18e93946" width="30%" />
  <img src="https://github.com/Mudit-pip/EditCall-Log/assets/70972592/5b43d1a0-3c22-42a8-abee-1134aa7b19c2" width="30%" />
</p>

<p float="left">
  <img src="https://github.com/Mudit-pip/EditCall-Log/assets/70972592/482e92f3-f0ef-4166-ad6a-e17252905f66" width="30%" />
  <img src="https://github.com/Mudit-pip/EditCall-Log/assets/70972592/1136c755-8b2c-4b3e-8315-7fc13cead733" width="30%" />
  <img src="https://github.com/Mudit-pip/EditCall-Log/assets/70972592/bed90c4a-de86-4cc8-a0ab-fe3b63d767f5" width="30%" />
</p>

## Demo

https://github.com/Mudit-pip/EditCall-Log/assets/70972592/f96ff2b0-306a-4e39-9de6-5b47707d525d

## Installation

### Option 1: Download APK

Download the latest APK from the [Releases page](https://github.com/Mudit-pip/EditCall-Log/releases) — the **"Latest Build"** release is automatically updated on every push. You can also download build artifacts from the [Actions tab](https://github.com/Mudit-pip/EditCall-Log/actions).

### Option 2: Build from source

```bash
git clone https://github.com/Mudit-pip/EditCall-Log.git
cd EditCall-Log
./gradlew assembleDebug
# APK will be at app/build/outputs/apk/debug/
```

> **Note for Windows:** This project uses a project-local Gradle cache (`.gradle-home/`) and Android SDK (`android-sdk/`) to avoid system pollution. If `services.gradle.org` is not reachable, download `gradle-8.0-bin.zip` from a [Chinese mirror](https://mirrors.cloud.tencent.com/gradle/) and place it in `.gradle-home/wrapper/dists/gradle-8.0-bin/ca5e32bp14vu59qr306oxotwh/`.

## Contributing

Contributions are always welcome!

Have ideas on how to improve **EditCall Log**?
Please send your suggestions to `mudit292005@gmail.com`, and let's make EditCall Log better together.


