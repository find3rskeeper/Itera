# Privacy Policy for Itera

**Last Updated: August 20, 2026**

This Privacy Policy describes how **Itera** ("we", "our", or "the App") handles user information and data. We are committed to protecting your privacy and ensuring you have complete control over your personal data.

---

## 1. Summary (Privacy-First Architecture)

- **100% On-Device Storage**: All habit definitions, completions, checklist logs, streak histories, and notes are stored locally on your device using a private SQLite database.
- **No Account Required**: You do not need to create an account, log in, or provide personal credentials (like your name or email address) to use the App.
- **Zero Data Collection**: We do not operate external tracking servers, analytics endpoints, or remote profiling databases. We do not sell, rent, or monetize your data.

---

## 2. Information We Handle

### A. Habit and Activity Data (Stored Locally Only)
When you use Itera, you may enter data such as:
- Habit titles, categories, frequencies, and target points.
- Sub-items and checklists.
- Completion records, streaks, and timestamps.
- Pause schedules and reminder times.

All of this data resides exclusively in your device's private sandboxed app storage. It is never uploaded to external servers or accessible by us.

### B. Backup & Export Data
The App provides an optional **Backup & Restore** feature:
- When you export your data, the App creates a JSON file using Android's standard system file picker (*Storage Access Framework*).
- You retain complete ownership and control over where this file is saved (e.g., local downloads folder, personal cloud drive).
- We do not have access to your exported backup files.

---

## 3. Device Permissions

Itera requests only the minimum permissions necessary to function:

- **Notifications (`POST_NOTIFICATIONS`)**: Used solely to deliver your scheduled local daily reminder alerts (Morning Kickoff and Evening Check-in). All reminders are scheduled and triggered on-device using Android's `AlarmManager`.
- **Exact Alarms (`SCHEDULE_EXACT_ALARM` / `USE_EXACT_ALARM`)**: Used to trigger reminder notifications precisely at the times you configure.

We do **not** request access to your location, camera, microphone, contacts, or device identity.

---

## 4. Third-Party Services & Analytics

- **No Third-Party Advertising**: Itera does not contain third-party ad networks.
- **No Third-Party Analytics / Trackers**: The App does not include tracking SDKs.

---

## 5. Data Retention & Deletion

Because all data is stored on your device:
- You have full control to edit or delete any individual habit or completion log at any time.
- Uninstalling the App or clearing the App's storage via Android Settings will permanently erase all local data from your device.

---

## 6. Children’s Privacy

Itera does not collect personal information from anyone, including children under the age of 13.

---

## 7. Changes to This Privacy Policy

We may update our Privacy Policy from time to time. Any updates will be posted to this page with an updated "Last Updated" date.

---

## 8. Contact Us

If you have any questions or feedback regarding this Privacy Policy, you can reach out via:
- **GitHub**: [https://github.com/](https://github.com/) (or your project repository issue tracker)
- **Email**: [njain4u@gmail.com](mailto:njain4u@gmail.com)
