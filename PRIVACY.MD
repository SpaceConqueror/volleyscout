# Privacy Policy for VolleyScout

**Last Updated: May 23, 2026**

This Privacy Policy describes how the "VolleyScout" mobile application manages, processes, and protects user data. 

VolleyScout is designed with a "privacy by design" approach. It does not use external databases or proprietary servers to store user information, ensuring that users maintain absolute ownership and control over their data.

---

## 1. Data Controller
Since the application does not collect, transmit, or store personal data on any server owned or controlled by the developer, data processing occurs entirely on the user's device and their personal cloud storage.

For any questions or concerns regarding this policy, you can contact the developer at:
**Email:** [cristian.racioppo@gmail.com](mailto:cristian.racioppo@gmail.com)

---

## 2. Types of Data Processed

### A. Game Data and Statistics (Non-Personal Data)
The application allows you to enter volleyball team info, player rosters, matches, in-game actions, and statistics.
* **Local Storage:** All this data is saved locally on your device's storage (using standard secure preferences) and is not sent to any developer-managed server.
* **File Import:** You can optionally import roster data via local files (e.g., CSV). This process is executed entirely offline on your device.

### B. Google Sign-In & Cloud Sync (Optional)
The application offers an optional feature to sync and backup your data to your personal **Google Drive** storage. If you choose to enable this feature:
* **Authentication:** The app uses Google Sign-In to connect to your account. This processes your Google Email Address and Google User ID to authenticate the connection.
* **Google Drive API (`drive.file` scope):** The app requests a highly restricted access scope (`https://www.googleapis.com/auth/drive.file`). This permission allows VolleyScout to access, create, or update **only** the specific files created by the app itself (the `/volleyscout` directory containing `preferences.json`, `teams.json`, and `matches.json`). The developer has no access to any of your other files, folders, or personal information on your Google Drive.

---

## 3. Data Sharing
We **do not share** your data with third parties. There are no third-party SDKs for advertising, user analytics, or behavior tracking integrated into the app. 

Any exchange of rosters or match files between users is done entirely manually and outside the application at the user's discretion.

---

## 4. Data Security
* **Encryption in Transit:** When syncing with Google Drive, data is transmitted securely using the encrypted HTTPS protocol managed by official Google APIs.
* **Local Security:** Local data on your device is protected by the native security mechanisms of your operating system (Android/iOS).

---

## 5. User Rights and Data Deletion Instructions
You have absolute control over your data and can request or execute its deletion at any time.

### How to Delete Your Data:
1. **Local Data:** You can delete all local data by clearing the application's storage in your device settings or by uninstalling the application.
2. **Google Drive Sync Files:** If you enabled cloud backup, you can delete the backup files by opening your Google Drive and permanently deleting the folder named `volleyscout`.
3. **Revoking Google Account Access (Account Disconnection):**
   To disconnect the application from your Google Account and revoke all permissions:
   * Go to your Google Account settings page at [myaccount.google.com](https://myaccount.google.com/).
   * Navigate to **Security** on the left menu.
   * Scroll down to **Third-party apps with account access** (or **Connections to third-party apps and services**).
   * Find and click on **VolleyScout**.
   * Click **Remove Access** (or **Delete all connections**).
4. **Assistance:** Since the developer has no backend database, there is no copy of your data on any external server. However, if you require assistance with the steps above, you can contact us at [cristian.racioppo@gmail.com](mailto:cristian.racioppo@gmail.com) and we will gladly guide you through the process.
