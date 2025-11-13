# Expo Go Setup Guide

## Overview
Unlike web development, mobile development relies on device emulators to test applications. However, keeping up with the ever-evolving mobile ecosystem (e.g., iPhone 7 → iPhone 16 Pro Max, and various Android devices) can be costly in terms of hardware requirements.

**Expo Go** provides a cost-effective solution by allowing developers to test and run React Native applications directly on their **physical devices**, supporting both **iOS** and **Android** seamlessly.

---

## Steps to Install Expo Go

1. **Visit the official Expo Go homepage:**  
   [https://expo.dev/go](https://expo.dev/go)

2. **Select the latest SDK version** to ensure compatibility with your React Native project.

3. **Install the Expo Go app for your device:**
   - **Android:** [Install from Google Play Store](https://play.google.com/store/apps/details?id=host.exp.exponent)
   - **iOS:** [Install from Apple App Store](https://apps.apple.com/app/expo-go/id982107779)

4. **Open the Expo Go app** on your mobile device.

5. **Sign in or create an account** if you don’t have one already.

6. **Connect your device and development environment:**
   - Make sure your **computer and mobile device are on the same Wi-Fi network.**
   - Run your project using:
     ```bash
     npx expo start
     ```
   - Scan the generated QR code with the Expo Go app.

---

## Challenges Faced

- **Network connectivity:**  
  Occasionally, the Expo Go app could not detect the local development server due to firewall or Wi-Fi issues. Switching to a mobile hotspot or using the **Tunnel** connection mode helped.


- **Device compatibility:**  
  Older Android devices may have performance issues or unsupported APIs when running newer SDKs.

---

## Summary

Expo Go simplifies mobile app testing by removing the need for physical device variations or emulators. It streamlines the development process, especially for cross-platform React Native projects, while keeping setup costs low.

---

**Repository:** [prodev-mobile-setup](https://github.com/mualu-ko/prodev-mobile-setup)  
**Directory:** `mobile-development-setup`  
**File:** `README.md`
