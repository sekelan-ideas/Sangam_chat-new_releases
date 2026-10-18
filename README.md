# Sangam — Downloads

**Where friends and family meet.**

This repository serves the ready-to-install Android builds of **Sangam**, a
private, end-to-end encrypted messenger built for families and small groups.
The source code lives in a private repository; this one exists only to
distribute the app.

---

## Download

**Always the newest version:**

> **[Download Sangam.apk](https://github.com/sekelan-ideas/Sangam-releases/releases/latest/download/Sangam.apk)**

**A specific version** — choose one on the
[Releases page](https://github.com/sekelan-ideas/Sangam-releases/releases),
or link straight to it:

```
https://github.com/sekelan-ideas/Sangam-releases/releases/download/v2.7.3/Sangam-v2.7.3.apk
```

## Install

1. Download the APK on your Android phone.
2. Open it. Android will ask you to allow installs from this source — allow
   it for your browser or file manager.
3. Tap **Install**, then open Sangam.

Requires **Android 8.0 (Oreo) or newer**.

## Updating

Install the new APK over the old one — every release is signed with the same
key, so Android updates in place and your chats are kept.

## Checking a download

```bash
sha256sum Sangam-v2.7.3.apk
```

Each release note lists the expected hash, so you can confirm the file
arrived intact.

## What's new

### 2.7.3
- Signing out now wipes the previous account's chats from the phone.
- Notifications say what actually arrived — photo, video, voice note or text.
- Password reset links open a "Set a new password" screen.

### 2.7.2
- Email confirmation and reset links now come back to the app instead of localhost.

### 2.7.1
- Forgot password, show-password button, and confirm-password on sign-up.

### 2.7.0
- Linked devices: every phone and tablet on your account is listed.

### 2.6.0
- View-once "Opened" receipts, server-side clearing of disappearing messages, smoother screen transitions.

### 2.5.0
- Photos stay in memory so reopening a chat is instant; a per-photo HD option.

Older releases are listed on the [Releases page](https://github.com/sekelan-ideas/Sangam-releases/releases).

## Privacy

Sangam stores **ciphertext only**. Messages, photos, videos and files are
encrypted on your device before they are uploaded, and keys never leave the
phone. No phone number is required.

---

*This repository contains build outputs only — no source code.*
