---
layout: page
title: Privacy Policy — BabyRaven
nav: false
---

# Privacy Policy for BabyRaven

**Last updated:** June 24, 2026

## Introduction

This Privacy Policy describes how BabyRaven ("we", "our", or "the app") handles your information. BabyRaven is developed by Maxime Van den Kerkhof.

## Our Privacy Commitment

BabyRaven is designed to keep your family's data safe. All tracking data is stored on your device and, when co-parent sharing is enabled, synced through Apple's iCloud — we do not operate our own servers or store your data externally.

## Information We Collect and Store

BabyRaven stores the following data **locally on your device and in iCloud (via CloudKit)**:

### Baby Profile
- Baby's name, date of birth, and sex — used to personalise the app and calculate age-appropriate sleep windows and growth percentiles.

### Tracking Data
- **Feeding sessions** — breastfeeding side, duration, bottle volume, and timestamp
- **Diaper changes** — type (wet/dirty/both) and timestamp
- **Sleep sessions** — start and end times
- **Measurements** — weight, height, and head circumference with dates

This data is stored locally using SwiftData and may be synced to your personal iCloud account via CloudKit private database. It is never accessible to us.

## Co-Parent Sharing (CloudKit)

If you choose to share your baby's tracking data with a co-parent, the data is shared through Apple's CloudKit using a private shared zone — the same technology used for sharing Apple Notes. This means:

- Sharing requires both parties to have an Apple ID.
- Data is transmitted and stored on Apple's servers under Apple's privacy policies.
- Only people you explicitly invite can access the shared data.
- We have no access to your shared data.

## AI Chat Feature

BabyRaven includes an optional AI chat feature powered by Claude (Anthropic). When you use this feature:

- A summary of your baby's **recent tracking data** (feedings, sleep, diapers, measurements, and baby profile) is included in the request to provide contextual responses.
- This data is sent to **Anthropic's API** (`api.anthropic.com`) over an encrypted HTTPS connection.
- Your API key is stored securely in the iOS **Keychain** and is never stored in the app's code or transmitted to us.
- Anthropic's data handling is governed by [Anthropic's Privacy Policy](https://www.anthropic.com/privacy).
- You control when to use the chat feature; it is never triggered automatically.

## Notifications

BabyRaven may send local push notifications for reminders and alerts. Notification preferences are managed on your device.

## Data We Do Not Collect

- We do not collect analytics or usage data.
- We do not use advertising networks.
- We do not track your location.
- We do not have access to any of your baby's data stored in iCloud.

## Children's Privacy

BabyRaven is intended for use by parents and caregivers — not by children. The app stores information *about* infants as entered by parents. We do not knowingly collect personal information directly from children.

## Data Security

All data is stored locally on your device or in your personal iCloud account. Your Anthropic API key, if provided, is stored exclusively in the iOS Keychain. We do not operate any external servers or databases.

## Changes to This Policy

We may update this Privacy Policy from time to time. Any changes will be reflected on this page with an updated date.

## Contact Us

If you have questions about this Privacy Policy, please contact:

**Maxime Van den Kerkhof**  
Email: maxime.vandenkerkhof@gmail.com
