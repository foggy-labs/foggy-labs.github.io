---
layout: default
title: CleanSnap - Privacy Policy
favicon_emoji: "📷"
---

# CleanSnap - Privacy Policy

**Last Updated: October 26, 2026**

CleanSnap ("we," "us," or "our") operates the CleanSnap mobile application (the "App"). This Privacy Policy explains how we collect, use, disclose, and safeguard your information when you use our App. Please read this policy carefully. If you do not agree with the terms of this Privacy Policy, please do not access the App.

**Version coverage.** The feature and control descriptions below apply to CleanSnap 1.3.1, including TestFlight build 12. The App Store may still offer 1.3 until the update is released. Version 1.3 initializes PostHog analytics at launch and can automatically record application lifecycle and screen-view events; it does not have the new Share Usage Analytics control. Version 1.3 can also offer Gmail sign-in and cleanup, with an in-app sign-out control. In 1.3.1, analytics is off by default and Gmail cleanup/sign-out is hidden. Where relevant, older-version behavior is retained below.

## 1. Information We Collect

### Permission-Based Features

**Photos and videos.** With Photos access, CleanSnap analyzes media on your device to find matching or similar photos, screenshots, blurry photos, and videos. Compression creates a new copy. CleanSnap does not upload photo or video content to Foggy Labs or analytics services. Apple Photos may download iCloud resources to your device. Review items before removing originals; resource-size estimates do not guarantee recoverable device space.

**Contacts and calendars.** Contact Cleanup accesses contacts with your permission, creates a local vCard backup, and lets you combine supported details or explicitly delete contacts. Calendar Cleanup uses calendar permission to review and remove selected events. These contents are processed locally and are not sent to analytics services. You can export contact backups using the iOS share sheet; the destination you choose then handles that copy.

**Private vault.** Imported media and its index are stored in the app's protected local files, excluded from device backup, and accessed through device authentication. Keep another copy of important media: removing the app or losing its data can make vault items unrecoverable. Vault export saves a copy to Photos.

**Gmail in version 1.3 and earlier.** Gmail cleanup is unavailable in 1.3.1. Version 1.3 and earlier offered a Google connection with Gmail read/modify access and access to the connected address. Those versions requested message IDs and metadata such as sender, subject, date and unsubscribe headers, not message bodies or attachments for cleanup. OAuth tokens may remain in the iOS Keychain and the connected address in app preferences after updating; 1.3.1 does not erase historical credentials or modify mailboxes. To disconnect a previous authorization, revoke CleanSnap's access in your Google Account. Revocation prevents further authorized access; it does not erase historical credentials stored on this device. Historical Gmail changes remain managed by Google. Gmail metadata is not sent to PostHog or used to train AI models.

**Communications.** If you contact our support team, we receive the content and information you choose to provide.

### Purchases and Optional Analytics

**Purchases.** Apple and RevenueCat process purchase and subscription information, subscription status, and app-user identifiers to verify Pro access and restore purchases. Disabling optional analytics does not disable purchase verification.

**Optional usage analytics.** In 1.3.1, Share Usage Analytics is off by default. If you enable it in CleanSnap Settings, PostHog receives the app events we record, including onboarding and permission outcomes, feature and purchase interactions, cleanup item counts, estimated media sizes, timestamps, and SDK device/application context such as operating-system and app versions. Events also include a random installation/anonymous identifier to associate activity. Network providers can receive the IP address used to contact them; analytics infrastructure may derive approximate geographic information from that address. We do not request GPS location for analytics. We do not send photos, contact details, calendar content, email content, or Gmail credentials to PostHog. Automatic screen capture, session replay, and element-interaction capture are disabled. Turning the setting off stops future optional usage analytics and clears the SDK's local analytics storage; it cannot recall requests already transmitted or erase data previously received by a provider.

**Network tools.** When you start Speed Test, CleanSnap downloads and uploads about 9 MB of generated test data to Cloudflare’s speed.cloudflare.com endpoints. It does not send your photos, contacts, calendar content, or email content. Cloudflare receives network request information, including your IP address. This traffic occurs when you start that tool and is separate from optional usage analytics.

### Information We Do NOT Collect

- CleanSnap does not upload photo/video content, contact details, or calendar content to Foggy Labs or analytics providers.
- We do not request microphone or Health access, or use a device-location permission to track your real-time position. Media may contain existing location metadata, which can be retained in saved media copies.
- The app does not initialize advertising-attribution SDKs or request an advertising identifier (IDFA).
- We do not send your media or connected Gmail content to third-party AI models.

## 2. How We Use Your Information

We use the information we collect to:

- Provide, operate, and maintain the App and its features, including local photo/video review, compression, contact and calendar cleanup, the private vault, and recovery guidance for historical activity
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
| Google OAuth / Gmail API (earlier versions) | Historical Gmail authorization and account changes; cleanup unavailable in 1.3.1 | Previously saved OAuth credentials, account address, message metadata and trash requests |
| [Cloudflare Speed Test](https://www.cloudflare.com/privacypolicy/) | Network test requests | Request information, including your IP address, and generated test data |

We do not sell your personal data to any third party. We do not upload or share your photos with advertising networks or third-party services. We do not provide your data to third-party AI models or machine learning services.

Each provider also handles information under its own terms and privacy policy.

## 5. Data Retention

Local preferences, histories, and backups remain in the app until removed or the app's data is deleted. Vault items are excluded from device backup; export important items before removing the app. Photos, contacts, calendar events, and Gmail changes are managed by their respective system or account stores and can remain after uninstalling CleanSnap. Exported contact backups remain wherever you saved them.

Gmail cleanup and its sign-out screen are unavailable in 1.3.1. In version 1.3, you can use Email Cleanup’s sign-out control to remove credentials saved by the app, or revoke access in your Google Account. If you previously connected Gmail, revoke CleanSnap's access in your Google Account. iOS Keychain items can survive app removal; revoking access does not erase previously saved credentials on this device. Turning off optional analytics does not delete data already sent. Provider-side retention depends on the provider's configuration and obligations; contact us about access or deletion of information previously received.

## 6. Data Security

We implement reasonable administrative, technical, and physical safeguards to protect your personal data, including:

- CleanSnap performs photo analysis locally and does not upload media to its servers
- All data stored locally using iOS system-level encryption
- Media, contact, and calendar contents are not sent to analytics providers; purchase requests and historical Gmail connections use the providers described above

No method of electronic transmission or storage is 100% secure. While we strive to protect your personal data, we cannot guarantee its absolute security.

## 7. Your Rights and Choices

Depending on your location, you may have the following rights:

- **Access.** Review local content in the relevant system store or app feature. Provider-side information is subject to the access processes of that provider.
- **Deletion.** Removing the app removes its app-container data, but does not undo changes in Photos, Contacts, Calendar, or Gmail, remove exported copies, cancel subscriptions, or necessarily remove Keychain items. Revoke any previous Google authorization separately; the Gmail sign-out screen is unavailable in 1.3.1.
- **Optional Analytics (1.3.1).** In CleanSnap, open Settings and turn off Share Usage Analytics. It is off by default and your choice persists across launches. The iOS advertising-tracking setting is separate and does not control PostHog usage analytics. Purchase verification and requests you make through network tools remain separate from this choice. Gmail cleanup is unavailable in 1.3.1.

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
- **Consent:** For optional usage analytics in 1.3.1 and optional features like push notifications

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

This Privacy Policy is effective as of October 26, 2026.
