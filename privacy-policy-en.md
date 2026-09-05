# Privacy Policy

**App Name**: Self Discipline (自律一下下)  
**Developer**: Riping Chen  
**Bundle ID**: bichen.disciplinedMaster.com  
**Effective Date**: September 5, 2026  
**Last Updated**: September 5, 2026

---

Welcome to **Self Discipline** (the "App"). We take your privacy seriously. Please read this Privacy Policy carefully before using the App.

## 1. Scope

This Privacy Policy applies to the Self Discipline macOS desktop application downloaded from the Mac App Store and its related services.

## 2. Information We Collect

### 2.1 Information You Provide

When using the App, you may voluntarily enter or upload:

- **Status records**: hourly body status, emotional status, composite scores
- **Events and tasks**: daily events, task content, completion status, reflections, suggestions
- **Timer records**: multi-task timer history, Pomodoro/stand-up reminder sessions
- **Diet management**: meal records, food names, calories, macronutrients, ratings, notes, food photos
- **Exercise and sleep** (if used): exercise and sleep records
- **Notes and bookmarks**: rich-text notes, web bookmarks
- **Calendar reminders**: reminder content you create
- **Feedback**: text feedback you submit
- **Settings**: city name, optional email, and other preferences

### 2.2 Automatically Collected Information

- **iCloud account identifier**: The App uses Apple iCloud CloudKit to identify your account via Apple's assigned `recordName`. We do not collect or store your Apple ID password
- **Device and usage preferences**: UI language, theme, sidebar state, timer sounds and colors, stored locally
- **Local timer history**: multi-task timer execution records (task name, duration, result, date)

### 2.3 Information We Do NOT Collect

- We do not collect your Apple ID password or iCloud credentials
- We do not use third-party advertising or analytics SDKs (e.g., Firebase Analytics)
- We do not collect precise geolocation (city name is manually entered by you for optional weather features)
- We do not sell your personal information to third parties

## 3. How We Use Information

We use collected information solely to:

1. **Provide core features**: store and sync your discipline records, tasks, diet, notes, and other data
2. **Cross-device sync**: synchronize data across your Apple devices via iCloud
3. **Improve user experience**: remember UI preferences, timer settings, etc.
4. **Local network image sync**: serve diet photos to your mobile devices on the same Wi-Fi network
5. **Process feedback**: store and handle feedback you submit

## 4. Storage and Sync

### 4.1 iCloud CloudKit (Primary Storage)

Most App data is stored in **Apple iCloud CloudKit** private database, container ID `iCloud.disciplinedMaster.com`. Data is tied to your Apple ID and protected by Apple's Privacy Policy.

### 4.2 Local Storage

The following data is stored locally on your Mac:

- **SQLite database** (`~/Library/Application Support/自律一下下/data/personal-manager.db`): timer history; legacy diet data (migrated to iCloud when possible)
- **Local files**: diet photos and general images
- **Browser localStorage**: UI preferences, drafts, temporary state

### 4.3 Local Network Service

The App may run a local HTTP server on your LAN to sync diet photos with mobile devices on the same network. This service:

- Runs only when you use related features
- Is accessible only within your local network, not exposed to the public internet
- Uses Bonjour/mDNS (`_personal-manager-sync._tcp`) for device discovery

## 5. Sharing and Disclosure

### 5.1 Third-Party Services

| Service | Purpose | Data Shared |
|---------|---------|-------------|
| **Apple iCloud CloudKit** | Data storage and cross-device sync | All primary data you create in the App |
| **wttr.in** (optional) | Weather lookup (currently disabled in UI) | City name you enter |
| **Legacy server zhushouxy.top** (optional) | One-time historical data migration | Legacy username, password, and data to migrate (only when you initiate migration) |

We do not share your personal information with any other third parties.

### 5.2 Legal Requirements

We may disclose information when required by law, court order, or government authority.

## 6. Data Security

We protect your information by:

- Storing and transmitting data via encrypted Apple CloudKit
- Running the App in macOS sandbox with strictly controlled permissions
- Storing local databases and files in app-specific directories inaccessible to other apps
- Not using third-party advertising or tracking SDKs

No method of transmission or storage is 100% secure. We strive to protect your data but cannot guarantee absolute security.

## 7. Your Rights

You have the right to:

1. **Access and export**: view all data in the App; export features available for diet and other modules
2. **Modify and delete**: edit or delete any record within the App
3. **Stop syncing**: sign out of iCloud or uninstall the App to stop CloudKit sync
4. **Delete account data**: uninstalling removes local data; iCloud data must be managed via [iCloud settings](https://www.icloud.com) or Apple support
5. **Opt out of LAN sharing**: do not enable diet photo sync to avoid the local network service

## 8. Health-Related Data

The App allows you to record diet, exercise, sleep, and mood information. **This information is for personal discipline management only and does not constitute medical diagnosis, treatment advice, or professional health guidance.** Consult a healthcare professional for medical concerns.

## 9. Children's Privacy

The App is not directed at children under 13 (or the minimum age in your jurisdiction). We do not knowingly collect children's personal information. Contact us if you believe we have inadvertently collected such data.

## 10. Legacy Data Migration

If you use the "Legacy Data Migration" feature, you enter your old system's username and password. This information is used only once to fetch historical data from the legacy server (zhushouxy.top) and import it into iCloud. It is not persistently stored by the App after migration.

## 11. Changes to This Policy

We may update this Privacy Policy from time to time. For material changes, we will notify you in the App or via our GitHub repository. Continued use after updates constitutes acceptance.

## 12. Contact Us

For questions about this Privacy Policy:

- **Developer**: Riping Chen
- **GitHub Issues**: https://github.com/xiaodaxia1083394272/personalManager_PrivacyPolicyETC/issues

---

*The Chinese version is available at [privacy-policy-zh.md](./privacy-policy-zh.md).*
