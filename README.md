# Privacy Policy for Tiny Crime Scene

**Last updated:** October 30, 2026

**Tiny Crime Scene** ("we", "our", or "the App") is developed and published by **Triple Lime Saver**. This Privacy Policy explains how we collect, use, disclose, and safeguard your information when you use our mobile application on Android devices.

By using the App, you agree to the collection and use of information in accordance with this Privacy Policy. If you do not agree with any part of this policy, please do not use the App.

---

## 1. Information We Collect

### A. Personal Information Provided by You
* **Google Account Information:** When you sign in with Google, we authenticate your identity via Google Sign-In / Jetpack Credential Manager and Firebase Authentication. We collect your Google User ID (`uid`), email address, and profile name to create and maintain your detective dossier, cloud progress, and daily streak.

### B. Gameplay and Progress Data
* **Case History & Scores:** We store your case attempt records, including case IDs, verdict status (Solved, Partially Solved, Unsolved), clues discovered, score breakdowns, completion time, experience points (XP), and detective rank.
* **Streak & Timing Information:** Internal timestamps in UTC and your game day streak evaluated according to daily release boundaries.

### C. Automatically Collected Technical Data
* **Device Identifiers & Diagnostics:** Android version, device model, crash logs, and app performance metrics.
* **Network & Connectivity Status:** Network state checks (`ACCESS_NETWORK_STATE`, `INTERNET`) to manage offline case downloads and sync pending submissions upon reconnection.

### D. Third-Party Advertising (Google AdMob)
The App integrates **Google AdMob** to display Banner and Interstitial advertisements. Google AdMob may automatically collect and process:
* Android Advertising ID (GAID / AAID)
* IP address (coarse location)
* Ad interaction telemetry, impressions, and engagement metrics
* Diagnostics and anti-fraud fraud signals

For more information on how Google processes ad data, please review:
[Google Privacy & Terms for Partner Apps](https://policies.google.com/technologies/partner-sites) and [Google Privacy Policy](https://policies.google.com/privacy).

---

## 2. How We Use Your Information

We use the collected information for the following specific purposes:
1. **Provide and Maintain Gameplay:** To synchronize case files, track your detective rank, calculate daily streaks, and display game results.
2. **Account Management & Authentication:** To verify your identity and ensure your progress is preserved across devices or reinstalls.
3. **Monetization & Advertising:** To display banner and interstitial ads through Google AdMob in compliance with Google Play Developer Program policies.
4. **Notifications:** If you grant notification permissions (`POST_NOTIFICATIONS`), we send local reminders when a new daily crime scene case is released or when your streak is at risk.
5. **App Security & Fraud Prevention:** To protect against cheating, abuse, and automated scraping.

---

## 3. Data Storage, Retention, and Security

* **Local Storage (Room Database & DataStore):** Your crime scene downloads, draft investigations, and UI preferences are stored locally on your device in secure app-private storage.
* **Cloud Storage (Google Cloud / Firebase Firestore):** Your authenticated dossier and completed case submissions are stored in Google Cloud Firestore using strict security rules enforcing per-user ownership and encrypted transit (HTTPS/TLS).
* **Data Retention:** We retain your account and progress data for as long as your account remains active.

---

## 4. User Rights and Data Deletion

We respect your privacy rights and provide transparent, self-serve data management directly inside the App:

### In-App Data Management Options (Settings Screen):
1. **Reset Local Device Cache Only:** Deletes cached cases, clue history, and local preferences from your device storage without affecting your cloud profile.
2. **Delete Account & Cloud Data:**
   * Permanently deletes your user profile and all case attempt records from Firebase Firestore (`/users/{uid}` and `/users/{uid}/attempts/*`).
   * Clears all local Room database tables and preferences.
   * Signs you out of the App immediately.

You may also submit a data deletion request by emailing us at **triplelimesaver@gmail.com**. Requests will be processed within 30 days.

---

## 5. Third-Party Service Providers

We utilize trusted third-party service providers who process data in accordance with their respective privacy policies:
* **Google Play Services & Firebase (Google LLC):**
  * Firebase Authentication (Account sign-in)
  * Cloud Firestore (Database persistence)
  * [Google Privacy Policy](https://policies.google.com/privacy)
* **Google AdMob (Google LLC):**
  * Advertising delivery and monetization
  * [AdMob Privacy & Security](https://support.google.com/admob/answer/6128543)

---

## 6. Children's Privacy

The App is designed for general audiences and is not directed to children under the age of 13. We do not knowingly collect personally identifiable information from children under 13. If we discover that a child under 13 has provided us with personal information, we will promptly delete it from our servers.

---

## 7. Device Permissions

The App requests only necessary permissions:
* `INTERNET` & `ACCESS_NETWORK_STATE`: Required to sync daily cases, verify Google Sign-In, and display AdMob ads.
* `VIBRATE`: Provides haptic feedback when discovering clues in the crime scene (can be toggled off in Settings).
* `POST_NOTIFICATIONS`: Delivers opt-in daily case release notifications (Android 13+ runtime permission).

---

## 8. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Any changes will be posted on this page with an updated "Last updated" date. We encourage you to review this Privacy Policy periodically.

---

## 9. Contact Us

If you have questions, feedback, or requests regarding this Privacy Policy or your personal data, please contact:

* **Publisher:** Triple Lime Saver
* **Email:** triplelimesaver@gmail.com
* **App:** Tiny Crime Scene
