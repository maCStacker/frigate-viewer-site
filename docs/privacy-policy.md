# Privacy Policy — Frigate Viewer Pro

**Last updated:** March 6, 2026

## Overview

Frigate Viewer Pro ("the App") is a mobile application that connects to your self-hosted Frigate NVR instance. Your privacy is important to us. This policy explains what data the App collects, processes, and stores.

## Data Collection

### Data We Do NOT Collect
- We do **not** collect personal data
- We do **not** use analytics or tracking services
- We do **not** send any data to our servers or third parties
- We do **not** use advertising SDKs
- We do **not** have a backend server — the App communicates exclusively with your own Frigate NVR

### Data Stored Locally on Your Device
The App stores the following data **only on your device** using encrypted storage and shared preferences:
- **Server credentials** (URL, username, password, JWT token) — stored in encrypted storage (Android Keystore)
- **App settings** (language, download path, alert preferences, camera configuration) — stored in shared preferences
- **MQTT connection details** (host, port) — stored in shared preferences
- **Downloaded snapshots and video clips** — stored in the device's download folder

This data never leaves your device and is not accessible to us.

### Network Communication
The App communicates exclusively with:
- **Your Frigate NVR server** — via HTTP/HTTPS for API calls, video streams, and event data
- **Your go2rtc server** — via WebRTC (WHEP) for low-latency live streaming
- **Your MQTT broker** — for real-time event notifications

All network communication is between your device and your own self-hosted infrastructure. No data is sent to external servers.

### In-App Purchases
The App uses RevenueCat for optional tip jar purchases. RevenueCat processes purchase transactions through Google Play. RevenueCat's privacy policy can be found at: https://www.revenuecat.com/privacy/

### Notifications
The App can display local notifications for camera detection events. These notifications are generated entirely on-device based on data from your Frigate NVR. No push notification service (e.g., Firebase Cloud Messaging) is used.

## Camera and Video Data
The App displays live camera streams, recorded events, and snapshots from your Frigate NVR. This data is:
- Streamed directly from your Frigate NVR to your device
- Never routed through any third-party server
- Never stored by us

You are solely responsible for the operation of your Frigate NVR and compliance with local surveillance laws (e.g., GDPR, BDSG).

## Data Sharing
We do not share any data with third parties. The App has no capability to do so, as it has no connection to any server other than your own Frigate NVR.

## Data Retention
All locally stored data can be deleted by:
- Clearing the App's data in Android settings
- Uninstalling the App
- Manually deleting downloaded files from the download folder

## Children's Privacy
The App is not directed at children under 13. We do not knowingly collect data from children.

## Changes to This Policy
We may update this privacy policy from time to time. Changes will be posted on this page with an updated date.

## Contact
If you have questions about this privacy policy, please contact us via GitHub:
https://github.com/maCStacker/frigate-viewer/issues

## Open Source
Frigate Viewer Pro is developed by maCStacker. The App is free to use.
