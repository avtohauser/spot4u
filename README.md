# Spot4u
**High-performance Spotlight-inspired launcher for Android.**

Spot4u is a minimalist, system-level overlay launcher designed for efficiency and speed. It serves as a centralized search hub, replacing standard app drawers with an intelligent command-line interface built on Material 3 Expressive principles.

---

## Core Functionality

* **Unified Search**: Instant indexing of installed applications and system shortcuts.
* **Direct Communication**: Initiate phone calls directly from the search results via contact name matching.
* **Media Discovery**: Search local image metadata or execute deep-link queries into Google Photos for OCR and facial recognition.
* **In-line Utilities**: 
    * Real-time mathematical expression evaluation (exp4j integration).
    * Live currency conversion with local caching.
* **System Control**: Rapid navigation to Developer Options, Wireless Debugging, and network settings through keyword commands.
* **Advanced UI/UX**:
    * Native system-level blur (Android 12+).
    * Dynamic Color support (Material You).
    * Physics-based spring animations for fluid transitions.

---

## Installation

1. Navigate to the **Releases** section of this repository.
2. Download the `Spot4u-v1.0.apk` file.
3. Install the APK on your device (requires "Install from Unknown Sources" permission).
4. For optimal experience, deploy the "Pill" search widget to the primary home screen.

---

## Technical Configuration

The integrated Settings Panel allows for granular control over:
* **Background Blur**: Adjustable radius for the system-level overlay.
* **Overlay Dimming**: Customizable background alpha for improved legibility.
* **Theming**: Support for Light, Dark, and System-default modes.
* **Dynamic Color**: Toggle for Material You color palette synchronization.

---

## Privacy and Permissions

Spot4u is designed with privacy as a priority. All processing occurs strictly on-device:
* **Contacts**: Used only for local name matching and dialing.
* **Storage**: Used exclusively for MediaStore indexing.
* **Telephony**: Used only to initiate user-requested calls.
No data is collected or transmitted to external servers.

---

## Development

Built with:
* **Language**: Kotlin
* **UI Framework**: Jetpack Compose
* **Architecture**: MVVM with StateFlow
* **Minimum SDK**: Android 12 (API 31) for full feature support.

---
**License**: Open Source. If this project assists your workflow, please provide a star on GitHub.
