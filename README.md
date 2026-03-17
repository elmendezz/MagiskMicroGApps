# 🚀 MicroG Installer For Magisk: The Ultimate GApps Alternative

![GitHub stars](https://img.shields.io/github/stars/elmendezz/MagiskMicroGApps?style=for-the-badge)
![GitHub releases](https://img.shields.io/github/v/release/elmendezz/MagiskMicroGApps?style=for-the-badge&color=green)
![Maintenance](https://img.shields.io/badge/Maintained-Yes-brightgreen?style=for-the-badge)

## 📖 Introduction: Reclaiming Your Device
In the modern Android ecosystem, "Google Play Services" has become a double-edged sword. While it provides essential APIs, it also consumes massive amounts of RAM, drains battery life with constant background pings, and compromises user privacy through persistent tracking.

**MicroG Installer For Magisk** is a high-performance, systemless solution designed to replace the bloated proprietary Google framework with **MicroG**. This module is engineered for users who demand a clean, fast, and private Android experience without sacrificing app compatibility.

---

## 🔍 Deep Dive: What are GApps?
**GApps** (Google Applications) are the proprietary system-level apps that Google requires for its ecosystem. 

**The Problem:** Official GApps are "heavy," stay active 24/7, and are the main cause of lag on many devices (our beloved **"Potatoes"**).

**Our Solution:** This module replaces those heavy binaries with a lightweight, open-source re-implementation. You get push notifications and app compatibility without the telemetry or the RAM hogging.

---

## 📦 What's Inside? (Included Components)
This module provides a full-featured environment by including the following core components and services:

### 🧠 Core System
* **MicroG Services Core (GmsCore):** The heart of the project, providing Google API replacements.
* **MicroG Companion:** Ensures full system integration.
* **GsfProxy:** Legacy support for Google Cloud Messaging.
* **FakeGApps:** The engine that enables Signature Spoofing system-wide.

### 🛒 Store & Sync Services
* **Aurora Store:** A private, FOSS client for the Google Play Store library.
* **Aurora Services:** Enables seamless background app installations.
* **Google Contacts Sync:** Keep your people organized and synced.
* **Google Calendar Sync:** Never miss an event with native sync support.

---

## ⚡ Key Features & Technical Benefits

### 🏎️ Performance & RAM Management
Traditional Google Services can idle at 300MB-600MB of RAM. MicroG operates at a fraction of that (often under 50MB), leaving more room for your apps and games.

### 🔋 Battery Longevity
By minimizing "Wake Locks" and optimizing location requests, users typically see an increase of 15-20% in daily battery life.

---

## 📋 Requirements & Prerequisites
* **Hardware:** Your "Potato" (Any Android device supported by your root manager).
* **Root Manager:** Magisk (v24.0+), KernelSU, or APatch.
* **LSposed:** **Mandatory**. Required to enable "Signature Spoofing."
* **The Will:** You must actually want a faster device.

> [!CAUTION]
> Do NOT attempt to flash this via Recovery (TWRP, OrangeFox, etc.). This is a systemless module designed to be handled by the Root Manager environment only. Flashing via recovery will result in errors or a bootloop.

---

## 🛠 Installation Guide
1. **Download:** Grab the latest `.zip` from the [Releases](https://github.com/elmendezz/MagiskMicroGApps/releases) section.
2. **Install:** Open your manager (Magisk/KSU/APatch) -> Modules -> Install from storage.
3. **Configure:** Once installed, open the MicroG settings app to grant necessary permissions.
4. **Reboot:** Essential for the hooks to take effect.
5. **Enjoy:** Your device is now de-googled and optimized.

---

## 📅 Maintenance & Update Commitment
I am committed to providing the most cutting-edge experience:
* **⚡ Pre-releases (Bleeding Edge):** Updated **twice every day** (2x/day) to include the latest commits.
* **✅ Stable Releases:** Updated every **3 days** after stability verification.

---

## 🔧 Troubleshooting (Common Issues)

### 1. Signature Spoofing is not active
* **Fix:** Ensure LSposed is running and the "FakeGApps" module (included) is active in the LSposed Manager.

### 2. Push Notifications not working
* **Fix:** Go to MicroG Settings -> Cloud Messaging -> Ensure it is "ON". Dial `*#*#426#*#*` to check the status.

### 3. Aurora Store issues
* **Fix:** If you have trouble logging in or installing, ensure **Aurora Services** is granted system permissions and "Session Installer" is selected in Aurora settings.

---

## ❓ Frequently Asked Questions (FAQ)

**Q: Will this delete my data?**
A: No, it's systemless. But if you come from official GApps, clear the data of apps that depend on Google.

**Q: Can I use the Play Store?**
A: This module includes **Aurora Store**, which allows you to download any app from the Play Store library without the tracking and bloat of the official client.

---

**Stay fast. Stay private. Keep the Potato alive.**
