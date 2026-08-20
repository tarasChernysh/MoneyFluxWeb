# Privacy Policy — MoneyFlux

**Effective date:** August 20, 2026
**Last updated:** August 21, 2026

MoneyFlux ("the App") is developed and published by **Taras Chernysh**, an independent software developer based in Ukraine ("we", "us", "the Developer").

This Privacy Policy explains how MoneyFlux handles information. The short version: **MoneyFlux has no servers, no accounts, and no analytics. We never receive your financial data.**

---

## 1. Summary

| Question | Answer |
|---|---|
| Do we collect personal data? | **No.** |
| Do we have a server or backend? | **No.** The App runs entirely on your device. |
| Do we use analytics, ads, or tracking SDKs? | **No.** |
| Do we share data with third parties? | **No.** |
| Do you need an account to use MoneyFlux? | **No.** |
| Where is your data stored? | On your device, and — if you enable iCloud — in your own private Apple iCloud account. |

---

## 2. Information We Do Not Collect

We do not collect, transmit, sell, rent, or otherwise process any of the following:

- Your name, email address, phone number, or postal address
- Your bank credentials, card numbers, or banking logins (the App never asks for them and cannot connect to a bank)
- Your transactions, balances, categories, accounts, loans, recurring payments, notes, or tags
- Bank statement files (CSV/PDF) that you import
- Your device identifiers, advertising identifiers (IDFA), or location
- Usage analytics, behavioural events, session recordings, or crash telemetry sent to us

MoneyFlux contains **no advertising SDKs, no analytics SDKs, and no third-party tracking libraries**. The only third-party component bundled in the App is **FactoryKit**, an open-source dependency-injection library that operates purely as internal application code — it performs no networking and processes no user data.

---

## 3. Data You Create Inside the App

All content you create or import — accounts, transactions, categories, budgets, recurring payments, loans, tags, notes, and imported bank statements — is stored **locally on your device** in an app-private database (Apple Core Data).

Bank statement files that you import (for example PrivatBank or MonoBank CSV files, or OschadBank and Scotiabank PDF statements) are parsed **on your device**. The file contents are never uploaded anywhere. Once parsing is finished, MoneyFlux keeps only the transaction records you chose to import.

You remain the sole owner and controller of this data at all times.

---

## 4. iCloud Sync

If you enable iCloud sync, MoneyFlux uses Apple's **CloudKit private database** to synchronise your data between your own Apple devices.

- Data is stored in **your personal iCloud account**, not in any account or infrastructure belonging to the Developer.
- The Developer has **no access** to your iCloud container, and cannot read, export, or restore your data.
- Sync is handled entirely by Apple's frameworks and is governed by Apple's privacy practices. See Apple's Privacy Policy: <https://www.apple.com/legal/privacy/>
- You can disable iCloud sync at any time in the App's settings, or in iOS Settings → your Apple Account → iCloud.

## 5. Device Permissions and System Features

MoneyFlux may request the following, always with your consent, and always processed locally:

| Feature | Purpose | Leaves your device? |
|---|---|---|
| **Files access** | To let you pick a bank statement (CSV/PDF) for import | No |
| **Notifications** | Local reminders for upcoming recurring payments and loan due dates | No — scheduled locally by iOS |
| **Face ID / Touch ID / passcode** | To lock the App | No — authentication is performed by iOS; the App only receives a success/failure result and never sees your biometric data |
| **iCloud** | Optional sync between your devices | Only to your own iCloud account |

You can revoke any of these permissions at any time in iOS Settings.

## 6. App Store and Apple

MoneyFlux is distributed through the Apple App Store. Apple may collect information related to your download, device, and — if you have opted in to sharing analytics with developers — aggregated, anonymised crash and usage statistics. This collection is performed by Apple under Apple's own terms, not by us. Any such reports we may view in App Store Connect are aggregated and cannot be used to identify you or to see your financial data.

## 7. Payments

MoneyFlux is currently offered free of charge. If paid features or subscriptions are introduced in the future, all payments will be processed by **Apple** through the App Store. We will never receive or store your payment card details. This Policy will be updated before any such feature is released.

## 8. Children

MoneyFlux is not directed at children under 13 (or the equivalent minimum age in your country). Because we collect no personal data at all, we do not knowingly collect personal information from children.

## 9. Your Rights

### 9.1 General Rights (All Users)

Privacy laws such as the EU/UK **GDPR**, the Law of Ukraine "On Personal Data Protection", Canada's **PIPEDA**, and the **CCPA/CPRA** grant rights such as access, correction, deletion, portability, objection, and withdrawal of consent with respect to personal data held by a controller.

Because we hold **no personal data about you**, there is nothing for us to disclose, correct, export, or erase. In practice, these rights are exercised directly and immediately on your own device:

- **Access / portability** — your data is visible in the App; export functionality is provided in the App where available.
- **Correction** — edit or delete any record at any time inside the App.
- **Erasure** — deleting the App removes its local database from your device. If iCloud sync was enabled, you can additionally remove the App's iCloud data in iOS Settings → your Apple Account → iCloud → Manage Account Storage.
- **Objection / withdrawal of consent** — you can stop using optional features (including iCloud sync and notifications permissions) at any time.

### 9.2 European Economic Area (EEA) and UK Users (GDPR)

If GDPR applies to you, you may also have rights to restrict processing and to lodge a complaint with your local data protection authority.

For in-app financial records, the Developer is not a "data controller" in the traditional sense because this data is not transmitted to or stored by the Developer. If you enable iCloud sync, any processing in iCloud is governed by Apple's relationship with you under Apple's terms and privacy policy.

### 9.3 California Users (CCPA/CPRA)

MoneyFlux does not collect personal information from within the App, other than information inherently processed by Apple for App Store distribution and account operations under Apple's own policies.

In relation to the App itself, we do **not** collect identifiers, geolocation data, audio data, visual data, internet activity logs, or financial records on our servers, because we do not operate servers and do not receive your in-app data.

We do **not** sell personal information, do **not** share personal information for cross-context behavioral advertising, and do **not** discriminate against users for exercising applicable privacy rights.

To submit a CCPA/CPRA request, email **chernyshtaras94@gmail.com** with the subject line **"CCPA Privacy Request"**. We aim to respond within 30 days, or within timeframes required by applicable law.

### 9.4 Turkish Users (KVKK)

Under Turkey's **KVKK**, you may have rights to learn whether your personal data is processed, request information about purposes of processing, learn recipients/third parties, request correction, and request deletion.

Because your in-app data does not reach the Developer, these rights are generally satisfied by your direct control of data on your device and (if enabled) in your own iCloud account, and will be honored to the extent applicable.

### 9.5 Canadian Users (PIPEDA)

If **PIPEDA** applies to you, you may request access to, correction of, or deletion of personal information held by an organization. Because we do not receive or store your in-app personal data, such rights are generally exercised directly by you in the App and on your device.

## 10. Data Security

Your data is protected by iOS's built-in application sandbox and, when your device is locked with a passcode, by full-device encryption. iCloud data is encrypted in transit and at rest by Apple. You can enable an additional Face ID / Touch ID / passcode lock inside MoneyFlux.

Because your data never leaves your control, there is no central database of MoneyFlux users that could be breached. However, no method of electronic storage is completely secure, and you are responsible for keeping your device and Apple Account secure.

## 11. Data Retention

We retain nothing, because we receive nothing. Your data persists on your device (and, if enabled, in your iCloud account) until you delete it or uninstall the App.

## 12. International Transfers

Since no data is transmitted to us, there are no international transfers of your personal data by the Developer. Any transfer performed by Apple as part of iCloud sync is governed by Apple's terms.

## 13. Changes to This Policy

We may update this Privacy Policy from time to time — for example, if new features change how data is handled. The updated version will be posted on this page with a revised "Last updated" date. Material changes will additionally be announced in the App's release notes. Continued use of the App after an update constitutes acceptance of the revised Policy.

## 14. Governing Law and Jurisdiction

This Privacy Policy is governed by the laws of **Ukraine**, and disputes relating to this Policy are subject to the jurisdiction of the courts of Ukraine.

If you reside in a jurisdiction with non-waivable privacy rights (including under GDPR, CCPA/CPRA, KVKK, PIPEDA, or other applicable law), nothing in this section limits those mandatory rights.

## 15. Contact

Questions about this Privacy Policy or about MoneyFlux's data practices:

**Taras Chernysh**
Independent developer, Ukraine
Email: **chernyshtaras94@gmail.com**

For privacy rights requests, please email us with a clear subject line such as **"Privacy Rights Request"** and include:

- the email address associated with your Apple account usage (if relevant);
- your country/state of residence;
- the specific right you want to exercise (for example: access, correction, deletion, objection, restriction, or portability);
- any details needed to identify the relevant context of your request.

We aim to respond to all enquiries within 30 days, or within timeframes required by applicable law.
