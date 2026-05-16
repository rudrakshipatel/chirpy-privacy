# Privacy Policy for Chirpy

**Last updated: [TO BE FILLED ON LAUNCH DAY — e.g. May 2026]**

Chirpy ("the app", "we") is a puzzle-based alarm clock for Android, developed by Rudrakshi Patel. This policy explains what data the app handles and what it does not.

## Summary

Chirpy is built around a simple principle: your alarms are yours. We don't collect personal data, we don't have user accounts, and we don't send your information to any server. Everything stays on your device.

## What Chirpy does NOT collect

- We do not require you to create an account or sign in.
- We do not collect your name, email address, phone number, location, or any personally identifiable information.
- We do not collect or share any analytics about how you use the app.
- We do not show ads.
- We do not track you across apps or websites.

## Information stored on your device

Chirpy stores the following data locally on your device only. It never leaves your phone unless you explicitly export it (e.g. via the diagnostic email feature below):

- The alarms you create (time, label, days of the week, puzzle choice, etc.)
- Your in-app preferences (name, default difficulty, snooze duration, scan-item allowlist, etc.)
- Recent diagnostic logs (the last few hundred lines of internal app messages, kept temporarily for troubleshooting — see "Diagnostic logs" below)

This data is stored in Android's standard SharedPreferences and app file storage. Uninstalling the app removes all of this data.

## Camera

Chirpy uses your device's camera for the "Scan an item" wake-up puzzle. When this puzzle is active:

- The camera captures live frames that are processed entirely on your device using on-device machine learning (Google ML Kit).
- Frames are **never** saved to your device's gallery.
- Frames are **never** uploaded to any server.
- Once a frame has been processed, it is discarded.

The camera is only active while a puzzle is being solved. It is not used at any other time.

## Notifications and alarms

Chirpy requests permission to:

- Post notifications, so it can show the alarm notification.
- Schedule exact alarms, so your alarm rings at the time you set.
- Run a foreground service for short periods, so the alarm reliably plays its sound.
- Ignore battery optimizations (optional), so the OS does not delay or skip your alarm.

These permissions are used only for their stated purpose and are not used to collect any data.

## Diagnostic logs

Chirpy keeps a small buffer of recent in-app diagnostic messages (the last ~500 lines) on your device. These contain technical details such as when alarms were scheduled and whether snooze attempts succeeded. They never contain personal information.

You can manually send these logs to the developer using the "Send diagnostic logs" option in the Settings screen. This opens your default email app with the log buffer pre-filled. The logs are only sent if you tap Send in your email app — Chirpy does not transmit them automatically. If you send a diagnostic email, the contents are received by the developer's personal email and used solely to fix bugs.

## Children's privacy

Chirpy is not directed at children under 13. We do not knowingly collect any data, and the app has no features that would require collecting data from anyone of any age. The app is rated for general audiences but is most useful for people who set their own alarms.

## Third-party services

Chirpy uses the following third-party libraries, which run entirely on your device:

- **Google ML Kit (image labeling, object detection)**: used to recognize items in the scan-an-item puzzle. Runs offline; no data is sent to Google.
- **Google Fonts**: font files are cached locally on first use.

We do not use any third-party analytics, ad networks, or crash reporting services at this time. If we add a crash-reporting service in the future (such as Firebase Crashlytics for diagnosing crashes), we will update this policy and disclose what is collected.

## Changes to this policy

If we change how Chirpy handles data, we will update this page and update the "Last updated" date at the top.

## Contact

Questions or concerns about privacy? Email: rudrakshikpatel2007@gmail.com
