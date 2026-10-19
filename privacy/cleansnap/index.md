---
layout: default
title: CleanSnap - Privacy Policy
favicon_emoji: "📷"
---

# CleanSnap - Privacy Policy

**Last Updated: October 19, 2026**

CleanSnap ("we," "us," or "our") operates the CleanSnap mobile application (the "App"). This Privacy Policy explains how we collect, use, disclose, and safeguard your information when you use our App. Please read this policy carefully. If you do not agree with the terms of this Privacy Policy, please do not access the App.

## 1. Information We Collect

### Permission-Based Features

**Photos and videos.** With Photos access, CleanSnap analyzes media on your device to find matching or similar photos, screenshots, blurry photos, and videos. Compression creates a new copy. CleanSnap does not upload photo or video content to Foggy Labs or analytics services. Apple Photos may download iCloud resources to your device. Review items before removing originals; resource-size estimates do not guarantee recoverable device space.

**Contacts and calendars.** Contact Cleanup accesses contacts with your permission, creates a local vCard backup, and lets you combine supported details or explicitly delete contacts. Calendar Cleanup uses calendar permission to review and remove selected events. These contents are processed locally and are not sent to analytics services. You can export contact backups using the iOS share sheet; the destination you choose then handles that copy.

**Private vault.** Imported media and its index are stored in the app's protected local files, excluded from device backup, and accessed through device authentication. Keep another copy of important media: removing the app or losing its data can make vault items unrecoverable. Vault export saves a copy to Photos.

**Optional Gmail connection.** Signing in with Google authorizes Gmail read and modify access and access to your Google account email address. CleanSnap requests message IDs and metadata such as sender, subject, date, and unsubscribe headers directly from Google. It does not request message bodies or attachments for cleanup. Trashing selected messages changes your Gmail account and can affect other devices. Unsubscribe links open a website or mail application you choose. OAuth tokens are stored in the iOS Keychain; the connected address is stored in app preferences. Sign out in Email Cleanup to remove the app's saved credentials, or revoke access in your Google Account. Gmail metadata is used for these requested features and is not sent to PostHog or used to train AI models.

**Communications.** If you contact our support team, we receive the content and information you choose to provide.

### Purchases and Optional Analytics

**Purchases.** Apple and RevenueCat process purchase and subscription information, subscription status, and app-user identifiers to verify Pro access and restore purchases. Disabling optional analytics does not disable purchase verification.

**Optional usage analytics.** Share Usage Analytics is off by default. If you enable it in CleanSnap Settings, PostHog receives the app events we record, including onboarding and permission outcomes, feature and purchase interactions, cleanup item counts, estimated media sizes, timestamps, and SDK device/application context such as operating-system and app versions. Network providers can also receive the IP address used to contact them. We do not send photos, contact details, calendar content, email content, or Gmail credentials to PostHog. Automatic screen capture, session replay, and element-interaction capture are disabled. Turning the setting off stops future optional usage analytics and clears the SDK's local analytics storage; it cannot recall requests already transmitted or erase data previously received by a provider.

**Network tools.** When you start Speed Test, CleanSnap downloads and uploads about 9 MB of generated test data to Cloudflare’s speed.cloudflare.com endpoints. It does not send your photos, contacts, calendar content, or email content. Cloudflare receives network request information, including your IP address. This traffic occurs when you start that tool and is separate from optional usage analytics.

### Information We Do NOT Collect

- CleanSnap does not upload photo/video content, contact details, or calendar content to Foggy Labs or analytics providers.
- We do not request microphone or Health access, or use a device-location permission to track your real-time position. Media may contain existing location metadata, which can be retained in saved media copies.
- The app does not initialize advertising-attribution SDKs or request an advertising identifier (IDFA).
- We do not send your media or connected Gmail content to third-party AI models.

## 2. How We Use Your Information

We use the information we collect to:

- Provide, operate, and maintain the App and its features, including local photo/video review, compression, contact and calendar cleanup, the private vault, and optional Gmail cleanup
- Process your subscriptions and manage premium features
- Monitor and analyze usage trends and preferences to improve the App
- Detect, prevent, and address technical issues, fraud, and abuse
- Communicate with you about updates, support requests, and promotional offers related to the App (with your consent where required by law)
- Comply with legal obligations

## 3. Photo Processing

Photo analysis and compression occur on your device. Compression and vault import create copies; the app asks before deleting selected Photos originals. Compression can be lossy and may not retain every format capability or item of metadata. Review and keep originals when needed. The app does not transmit your photos to Foggy Labs or analytics providers; Apple Photos manages its own iCloud downloads and synchronization.

## 4. Third-Party Services

We use the following third-party services, each of which has its own privacy policy governing the data it processes:

| Service | Purpose | Data Processed |
|---------|---------|----------------|
| PostHog (optional) | Usage analytics when enabled | Recorded app events, aggregate cleanup estimates/counts, app/device context |
| RevenueCat | Pro access and purchase restoration | App-user identifiers, purchase/subscription information and status |
| Apple Photos / StoreKit | Photo-library access, iCloud resources, in-app purchases | The media and transactions needed for your requested actions |
| Google OAuth / Gmail API (optional) | Connect Gmail and perform selected account actions | OAuth credentials, account address, message IDs and metadata, trash requests |
| [Cloudflare Speed Test](https://www.cloudflare.com/privacypolicy/) | Network test requests | Request information, including your IP address, and generated test data |

We do not sell your personal data to any third party. We do not upload or share your photos with advertising networks or third-party services. We do not provide your data to third-party AI models or machine learning services.

Each provider also handles information under its own terms and privacy policy.

## 5. Data Retention

Local preferences, histories, and backups remain in the app until removed or the app's data is deleted. Vault items are excluded from device backup; export important items before removing the app. Photos, contacts, calendar events, and Gmail changes are managed by their respective system or account stores and can remain after uninstalling CleanSnap. Exported contact backups remain wherever you saved them.

Gmail sign-out removes the credentials saved by CleanSnap and resets its in-memory mailbox state. iOS Keychain items can survive app removal, so sign out or revoke Google access if you no longer want the connection. Turning off optional analytics does not delete data already sent. Provider-side retention depends on the provider's configuration and obligations; contact us about access or deletion of information previously received.

## 6. Data Security

We implement reasonable administrative, technical, and physical safeguards to protect your personal data, including:

- CleanSnap performs photo analysis locally and does not upload media to its servers
- All data stored locally using iOS system-level encryption
- Media, contact, and calendar contents are not sent to analytics providers; optional Gmail and purchase requests use the providers described above

No method of electronic transmission or storage is 100% secure. While we strive to protect your personal data, we cannot guarantee its absolute security.

## 7. Your Rights and Choices

Depending on your location, you may have the following rights:

- **Access.** Review local content in the relevant system store or app feature. Provider-side information is subject to the access processes of that provider.
- **Deletion.** Removing the app removes its app-container data, but does not undo changes in Photos, Contacts, Calendar, or Gmail, remove exported copies, cancel subscriptions, or necessarily remove Keychain items. Sign out of Gmail or revoke access separately.
- **Optional Analytics.** In CleanSnap, open Settings and turn off Share Usage Analytics. It is off by default and your choice persists across launches. The iOS advertising-tracking setting is separate and does not control PostHog usage analytics. Purchase verification and requests you make to Gmail or network tools remain available.

To exercise any of these rights or with questions, please contact us at npc@foggylabs.ai. We will respond within 30 days.

## 8. Children's Privacy

The App is not directed to children under the age of 13. We do not knowingly collect personal data from children under 13. If we learn that we have collected personal data from a child under 13, we will take steps to delete that data promptly. If you believe that a child under 13 has provided us with personal data, please contact us at npc@foggylabs.ai.

## 9. International Data Transfers

Your data may be processed in the United States or other countries where our service providers operate. By using the App, you consent to the transfer of your data to these jurisdictions, which may have data protection laws that differ from those in your country.

## 10. California Privacy Rights (CCPA/CPRA)

If you are a California resident, you have additional rights under the California Consumer Privacy Act (CCPA) and the California Privacy Rights Act (CPRA):

- The right to know what personal data we collect, use, and disclose
- The right to request deletion of your personal data
- The right to opt out of the sale of personal data — we do not sell your personal data
- The right to non-discrimination for exercising your privacy rights

To exercise these rights, contact us at npc@foggylabs.ai.

## 11. European Privacy Rights (GDPR)

If you are located in the European Economic Area (EEA) or United Kingdom, we process your data under the following legal bases:

- **Contract performance:** To provide the App and its features as described in our Terms of Service
- **Legitimate interests:** To improve the App, prevent fraud, and ensure security
- **Consent:** For optional features like push notifications

Under the GDPR, you have the right to:

- Access the personal data we hold about you
- Rectify inaccurate personal data
- Request erasure of your personal data
- Restrict or object to the processing of your personal data
- Data portability — receive your data in a structured, machine-readable format
- Withdraw consent at any time where processing is based on consent

You have the right to lodge a complaint with your local data protection authority if you believe your rights have been violated.

To exercise these rights, contact us at npc@foggylabs.ai. We will respond to verified requests within 30 days.

## 12. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of material changes by posting the updated policy in the App and updating the "Last Updated" date. Your continued use of the App after any changes constitutes your acceptance of the revised policy.

## 13. Contact Us

If you have questions about this Privacy Policy, please contact us:

**Email:** npc@foggylabs.ai

This Privacy Policy is effective as of October 19, 2026.
