---
title: Privacy Policy - VideoWeigh
description: Privacy Policy for the VideoWeigh mobile application
---

# Privacy Policy - VideoWeigh

**Last Updated:** 2 de Octubre de 2026

**Effective Date:** 2 de Octubre de 2026

---

## 1. Introduction

Welcome to VideoWeigh ("we," "our," or "us"). This Privacy Policy explains how we collect, use, disclose, and safeguard your information when you use our mobile application VideoWeigh (the "App").

Please read this privacy policy carefully. If you do not agree with the terms of this privacy policy, please do not access the App.

---

## 2. Information We Collect

### 2.1 Personal Information

We collect information that you voluntarily provide when you:
- Register for an account
- Participate in fishing competitions
- Use the App's features

This information may include:
- **Email address**: Used for account authentication and communication
- **Name**: Used for identification within competitions
- **Profile information**: Team membership and competition participation

### 2.2 Automatically Collected Information

When you use our App, we automatically collect:
- **Device Information**: Device model, operating system version
- **Location Data**: GPS coordinates when capturing fishing catches (only when you grant permission)
- **Usage Data**: App interactions for improving user experience
- **Notification Data**: If you allow notifications, a device notification identifier and related technical data (see Section 14)

### 2.3 Media Content

- **Videos and Photos**: Recorded fishing catches for competition verification
- **Thumbnails**: Generated previews of your captured videos

---

## 3. How We Use Your Information

We use the collected information for:

- **Authentication**: To create and manage your account
- **Competition Features**: To verify and record fishing catches
- **Synchronization**: To sync your data across devices
- **Anti-Fraud**: To verify the authenticity of captures using timestamp and location data
- **Communication**: To send important updates about competitions, including push notifications (see Section 14)
- **App Improvement**: To analyze usage patterns and improve our services

---

## 4. Data Storage and Security

### 4.1 Local Storage

- Your videos and capture data are stored locally on your device using SQLite database
- Videos are stored in the app's secure document directory
- Data syncs to our servers when internet connection is available

### 4.2 Cloud Storage

- User account data is stored in **Supabase** (PostgreSQL database)
- Videos are stored in **Cloudflare R2** cloud storage
- All data transmission is encrypted using HTTPS/TLS

### 4.3 Security Measures

- JWT authentication for API access
- HMAC token verification for anti-fraud system
- Row-Level Security (RLS) in database
- Encrypted storage for sensitive credentials

---

## 5. Data Sharing

We do not sell your personal information. We may share your data with:

### 5.1 Service Providers

- **Supabase**: Authentication and database services
- **Cloudflare**: Video storage and content delivery
- **Apple (Apple Push Notification service) and Google (Firebase Cloud Messaging)**: Delivery of push notifications to your device (see Section 14)

### 5.2 Competition Organizers

- Event organizers may access your competition-related data (captures, weights, rankings)
- Team members can see your captures within shared competitions

### 5.3 Legal Requirements

We may disclose information if required by law or to:
- Comply with legal processes
- Protect our rights and safety
- Prevent fraud or abuse

---

## 6. Your Rights

You have the right to:

### 6.1 Access
Request a copy of your personal data

### 6.2 Correction
Update or correct inaccurate information

### 6.3 Deletion
Request deletion of your account and associated data

### 6.4 Portability
Request your data in a portable format

### 6.5 Withdraw Consent
Revoke permissions for camera, microphone, location or notifications through your device settings or the App settings

---

## 7. Data Retention

- **Account Data**: Retained while your account is active
- **Competition Data**: Retained for the duration of the competition plus 12 months for dispute resolution
- **Videos**: Retained until you delete them or request account deletion
- **Usage Analytics**: Anonymized after 12 months
- **Notification Identifier**: Deactivated (no more notices are sent) when you sign out, when your session moves to another device, or after 90 days without the App registering it again (the App re-registers it every 7 days while in use). Permanently deleted 30 days after deactivation, or when your account is deleted (see Section 13)

---

## 8. Account Deletion {#account-deletion}

### How to Delete Your Account

You can permanently delete your VideoWeigh account directly from the app:

1. Open the VideoWeigh app
2. Go to **Settings** (gear icon)
3. Scroll down and tap **"Eliminar cuenta"** (Delete Account)
4. Confirm your decision when prompted

### What Data Is Deleted

When you delete your account, the following data is **permanently and immediately deleted**:

**From our servers:**
- All your videos and thumbnails stored in the cloud
- Your user profile and account information
- All capture records and competition data
- Authentication credentials

**From your device:**
- Local SQLite database
- Locally stored videos and thumbnails
- App cache and session data

### Data Retention After Deletion

- **Retention period**: None. All data is deleted immediately upon request.
- **Recovery**: Account deletion is **permanent and cannot be undone**.
- **Backups**: Deleted data is not retained in backups.

### Important Notes

- You must be logged in to delete your account
- Ensure you have an internet connection to complete the deletion
- If you are part of a team, your captures will no longer be visible to teammates after deletion

---

## 9. Children's Privacy

VideoWeigh is not intended for children under 13 years of age. We do not knowingly collect personal information from children under 13.

---

## 10. International Data Transfers

If you are accessing the App from outside Spain, your data may be transferred to and processed in other countries where our service providers operate, including Apple and Google (push notification delivery).

---

## 11. Changes to This Policy

We may update this Privacy Policy from time to time. We will notify you of any changes by:
- Posting the new Privacy Policy in the App
- Sending an email notification (for significant changes)

---

## 12. Contact Us

If you have questions about this Privacy Policy, please contact us at:

- **Email**: soporte@videoweigh.com
- **Website**: https://videoweigh.com *(Coming Soon)*

---

## 13. Specific Disclosures

### 13.1 California Residents (CCPA)

California residents have additional rights under the California Consumer Privacy Act (CCPA):
- Right to know what personal information is collected
- Right to delete personal information
- Right to opt-out of sale of personal information (we do not sell data)
- Right to non-discrimination

### 13.2 European Union Residents (GDPR)

EU residents have rights under the General Data Protection Regulation (GDPR):
- Right to access, rectification, and erasure
- Right to data portability
- Right to object to processing
- Right to lodge a complaint with a supervisory authority

**Legal Basis for Processing**: We process your data based on:
- Consent (for optional features)
- Contract performance (for core app functionality)
- Legitimate interests (for security and fraud prevention)

---

## 14. Push Notifications

If you allow notifications on your device, we use them to tell you about competitions you take part in and to remind you about catches.

### 14.1 What We Store

- **Device notification identifier** (push token): an identifier issued by Apple or Google that lets us send notifications to your device
- **Platform and provider**: whether your device uses Apple (iOS) or Google (Android)
- **Environment**: development or production
- **App identifier**: the identifier of the VideoWeigh app
- **App installation identifier**: generated when you install the App; it is not a hardware identifier
- **Date of last registration**: when the App last registered the identifier with us

We do not use this data to track you or to build advertising profiles.

### 14.2 Why We Use It

- Notices about changes to competitions you are part of (for example, changes to an event or its status), sent through our servers
- Reminders about catches that have not been uploaded. These are scheduled on your device itself: they do not send data to our servers and do not go through Apple or Google

### 14.3 Legal Basis

Performance of the service you requested (contract). We will only send marketing or promotional notifications with your prior consent.

### 14.4 Service Providers

Only notices about changes to events are delivered through **Apple Push Notification service** (iOS) or **Google Firebase Cloud Messaging** (Android). The identifier and the notification content pass through them, and they act as data processors on our behalf. Catch reminders do not use these services.

### 14.5 Retention

The notification identifier is deactivated, and no more notices are sent, when you sign out, when your session moves to another device, or after 90 days without the App registering it again (the App re-registers it every 7 days while you use it). Deactivated records are permanently deleted 30 days later. When your account is deleted, these records are deleted with it.

### 14.6 How to Turn Notifications Off

You can disable notifications at any time in the App settings or in your device's system settings. The App will keep working normally.

### 14.7 Lock Screen Visibility

The text of a notification may be visible on your device's lock screen. It may include the name, date and location of an event. It never includes weights or data of other participants. You can hide notification previews in your device's system settings.

---

*This Privacy Policy was last updated on 2 de Octubre de 2026*
