# Mathizzle — User Account & Data Deletion Request

**Effective Date:** August 20, 2026
**Application:** Mathizzle (`com.rawvi.mathizzle`)
**Developer:** Rawvi (`rawviai@gmail.com`)

---

## How to Request Account and Data Deletion

We provide two straightforward methods for users to permanently delete their account and associated data:

### Method 1: In-App Deletion (Recommended)

1. Open the **Mathizzle** game on your device.
2. Tap the **Settings** (⚙️) icon on the home screen or game screen.
3. Scroll down and tap **"Delete My Account"**.
4. Read the confirmation screen and tap **"Schedule Delete (72h)"**.
5. Your account will be permanently deleted within **72 hours**.

> **Grace Period:** You have 72 hours to change your mind. Simply open the app and tap **"Cancel Deletion & Keep Account"** in Settings to restore your account before the timer expires.

**What gets deleted:**
- Your cloud profile and Supabase account record
- Cloud-saved game progress (levels, coins, gems, badges, streaks)
- All personal data associated with your account

---

### Method 2: Email Request (If App Is Uninstalled)

If you have uninstalled the app or cannot access your device, you can request manual deletion of your account and cloud data:

1. Send an email to **rawviai@gmail.com**
2. Use the subject line: **"Account Deletion Request – Mathizzle"**
3. Include the **email address** associated with your Mathizzle account (Google or Apple login email)
4. We will permanently delete your account and all associated data within **72 hours** of receiving your request
5. You will receive a confirmation reply once deletion is complete

---

## What Data Is Deleted

Upon deletion, the following data is permanently removed:

| Data Type | Storage Location | Deleted? |
|---|---|---|
| Game progress (levels, coins, gems, badges) | Supabase cloud database | ✅ Yes |
| User profile (username, avatar) | Supabase cloud database | ✅ Yes |
| Authentication record | Supabase Auth | ✅ Yes |
| Daily streak & XP history | Supabase cloud database | ✅ Yes |
| Local device preferences | Device shared preferences | ✅ Yes (on reinstall) |

> **Note:** Data held by third-party services (Google Analytics, Firebase Crashlytics, AdMob) is governed by Google's own data retention policies and may be retained for a limited period per their terms.

---

## Contact

For any data-related questions or concerns, contact us at:
**rawviai@gmail.com**
