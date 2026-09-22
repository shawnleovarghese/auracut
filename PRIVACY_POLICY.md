# Privacy Policy for AuraCut - Video Editor & Pro Camera

**Last Updated:** September 22, 2026  
**Effective Date:** September 22, 2026  

Welcome to **AuraCut** ("AuraCut", "the App", "we", "us", or "our"), developed by Shawn Leo Varghese. We are deeply committed to protecting your privacy, data security, and digital sovereignty. This Privacy Policy explains how AuraCut handles, accesses, processes, and protects your information when you use our mobile applications (Android and iOS), desktop application, and companion tools.

Please read this Privacy Policy carefully. By downloading, accessing, or using AuraCut, you agree to the collection and use of information in accordance with this policy.

---

## 1. Core Privacy Philosophy: On-Device Sovereignty

AuraCut is architected with a **Privacy-First, On-Device Processing** philosophy:
* **No Cloud Uploads of Your Media:** Your personal photos, captured videos, recorded voiceovers, and edited timeline projects are stored, rendered, and processed **100% locally on your device** hardware. We do not operate remote servers that collect, store, or view your video content.
* **No Account Required for Editing:** You can use AuraCut's core video editing studio, Pro Camera, and media player without creating an account or providing your personal name or phone number.
* **Encrypted Private Vault:** Items moved to the AuraCut Secret Vault are stored locally with hardware-backed encryption (Android KeyStore / iOS Secure Enclave).

---

## 2. Information We Access, Collect, and Process

### A. Device Permissions & Purpose
To deliver pro-grade video editing, camera capture, and playback capabilities, AuraCut requests the following device permissions:

| Permission | Category | Purpose & Usage |
| :--- | :--- | :--- |
| **CAMERA** | Camera | Required to record high-resolution video (8K/4K/1080p), capture RAW/Pro photos in Pro Camera mode, and scan QR codes for Companion desktop pairing. Camera feeds are rendered in real time and never sent to external servers. |
| **RECORD_AUDIO** | Microphone | Required for capturing audio during video shoots, recording custom voiceovers in the timeline, and live VU audio monitoring. |
| **READ_MEDIA_VIDEO / IMAGES / AUDIO** (Android 13+) / **READ_EXTERNAL_STORAGE** | Media & Files | Required for browsing, previewing, and importing videos, photos, and music files from your local storage into the timeline editor or video player. |
| **WRITE_EXTERNAL_STORAGE** (Android 10 and below) | Storage | Required to export rendered MP4 video files and saved thumbnails to your device gallery or downloads folder. |
| **BODY_SENSORS / GYROSCOPE** | Motion Sensors | Used exclusively for 360° Real-Time Horizon Lock stabilization, gyro telemetry recording, and leveler overlays during Pro Camera shoots. Telemetry is saved within the local project only. |
| **USE_BIOMETRIC / USE_FINGERPRINT** | Biometrics | Used solely to authenticate your identity when unlocking your locally encrypted Secret Vault. Biometric verification is performed entirely by the secure OS hardware subsystem; biometric templates are **never** accessible to or stored by AuraCut. |
| **INTERNET / ACCESS_NETWORK_STATE** | Network | Required to serve third-party ads (Google AdMob), fetch IPTV streams entered directly by the user, and perform socket discovery with the Desktop Companion on your local Wi-Fi. |
| **ACCESS_WIFI_STATE / CHANGE_WIFI_MULTICAST_STATE** | Local Network | Enables local NSD (Network Service Discovery) / Bonjour pairing between your mobile device and your desktop editor on the same local subnet. Media remains on your local network. |

---

## 3. Third-Party Services & Advertising (AdMob & Analytics)

While your media remains local, AuraCut integrates trusted third-party software development kits (SDKs) to provide advertisements, crash diagnosis, and app improvement services. These third-party providers may collect certain technical device identifiers and interaction data.

### A. Google AdMob (Google LLC)
We use **Google AdMob** to display banner, interstitial, native, and rewarded advertisements. AdMob may collect and process:
* **Device Identifiers:** Google Advertising ID (AAID) on Android, Identifier for Advertisers (IDFA) on iOS, IP address, and device model/manufacturer.
* **Ad Interaction Data:** Views, clicks, impressions, and ad diagnostics.
* **Coarse Location Data:** Derived from IP address for regional ad delivery.
* **Consent Management:** In regions subject to GDPR (European Economic Area & UK) and CCPA/CPRA (California), AuraCut implements Google's User Messaging Platform (UMP) Consent Management Platform (CMP). You can choose personalized ads, non-personalized ads, or manage your tracking preferences directly within the app consent dialog or your device settings.

For more details on how Google processes ad data, please review:
* [Google Privacy Policy](https://policies.google.com/privacy)
* [How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/partner-sites)
* [Google AdMob Data & Privacy](https://support.google.com/admob/answer/6128543)

### B. Google Analytics for Firebase & App Analytics (Google LLC)
AuraCut uses **Google Analytics for Firebase (Google Analytics)** to understand app performance, stability, and aggregate user engagement patterns. Google Analytics collects:
* **Usage & Engagement Data:** Screen views, navigation paths, session duration, feature utilization (e.g., timeline export completed, filter applied, camera mode switched), and retention statistics.
* **Technical Device Data:** Device brand, model, operating system version, language settings, screen resolution, and anonymous Firebase App Instance IDs.
* **Diagnostic & Stability Telemetry:** App launch times, memory usage, rendering performance, and crash stack traces via Firebase Crashlytics & Google Play Console Vitals.

**Purpose & Protection:**
* All analytics data is processed in an **anonymized and aggregated form**.
* Analytics data is used exclusively to optimize rendering speed, resolve device-specific bugs, and improve user experience across diverse Android and iOS devices.
* Google Analytics **never** accesses, reads, analyzes, or uploads your personal video files, photos, audio recordings, or project content.
* For more information, please refer to the [Firebase Privacy & Security Documentation](https://firebase.google.com/support/privacy) and [Google Privacy Policy](https://policies.google.com/privacy).

---

## 4. Local Network Companion & Streaming Features

* **Desktop Companion Deck:** When using AuraCut Companion to control your desktop editing suite over Wi-Fi, timeline synchronization, jog-wheel commands, and video monitoring frames are transmitted directly over your local area network (LAN) using WebSockets. No companion traffic is routed through external cloud servers.
* **IPTV Stream Player:** When you enter a custom M3U playlist or stream URL into the AuraCut Player, the app streams content directly from that source URL to your device. AuraCut does not host, curate, log, or distribute copyrighted media streams.

---

## 5. Data Retention, Storage, and Security

* **Local Storage:** All video drafts, rendered exports, project packages, and database checkpoints are stored directly in your device's internal app sandboxed storage or designated gallery folders.
* **Vault Security:** Media items saved to the Secret Vault are encrypted with AES-256 and protected by your device's biometric authentication framework.
* **Data Deletion:** You have complete control over your data. You can delete individual projects, clips, or vault items within the app at any time. Uninstalling the app or clearing App Storage via your device's settings will permanently remove all locally cached projects and application data.

---

## 6. Children's Privacy (COPPA & Age Compliance)

AuraCut is a general-audience video production and editing tool. We do **not** knowingly collect, solicit, or maintain personally identifiable information from children under the age of 13 (or under 16 in the European Union). If we become aware that personal information from a child has been collected without verifiable parental consent, we will promptly take steps to delete such data.

---

## 7. Your Privacy Rights (GDPR, CCPA/CPRA, and International)

Depending on your geographic location, you may have specific legal rights regarding your personal information:

### A. European Economic Area (EEA) & UK Users (GDPR)
* **Right to Access & Portability:** You have the right to request information about any data collected by third-party SDKs.
* **Right to Rectification & Erasure:** You can clear local app data or request deletion of third-party advertising identifiers.
* **Right to Withdraw Consent:** You can revoke consent for personalized advertising at any time via the in-app consent settings or device privacy options.

### B. California Users (CCPA / CPRA)
* **Right to Know & Delete:** You have the right to request disclosure of categories of personal information collected by advertising partners.
* **Do Not Sell or Share My Personal Information:** AuraCut does not sell user media or personal profiles. For advertising identifiers, you can opt out of personalized tracking via your Android/iOS system advertising settings.

---

## 8. How to Opt-Out of Interest-Based Advertising

You can disable or reset personalized advertising IDs directly in your device settings:
* **Android:** Open **Settings** > **Google** > **Ads** (or **Privacy** > **Ads**) > Tap **Delete advertising ID** or **Reset advertising ID**.
* **iOS:** Open **Settings** > **Privacy & Security** > **Tracking** > Toggle off **Allow Apps to Request to Track**.

---

## 9. Changes to This Privacy Policy

We may update our Privacy Policy periodically to reflect new features, app updates, or legal requirements. When changes occur, the updated policy will be published on this page with an updated "Last Updated" date. We encourage you to review this Privacy Policy periodically.

---

## 10. Contact Us

If you have any questions, concerns, feedback, or data deletion inquiries regarding this Privacy Policy, please contact us at:

* **Developer:** Shawn Leo Varghese (AuraCut Development Team)
* **Email:** [shawnleovarghese@gmail.com](mailto:shawnleovarghese@gmail.com)
* **Project Repository:** [https://github.com/shawnleovarghese/video-editor](https://github.com/shawnleovarghese/video-editor)
* **Official Website:** [https://shawnleovarghese.github.io/video-editor/](https://shawnleovarghese.github.io/video-editor/)
