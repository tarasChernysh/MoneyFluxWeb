# Privacy Policy — MoneyFlux

**Effective date:** August 20, 2026
**Last updated:** August 20, 2026

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

Privacy laws such as the EU/UK **GDPR**, the Law of Ukraine "On Personal Data Protection", Canada's **PIPEDA**, and the **CCPA** grant you rights of access, correction, deletion, portability, and objection with respect to personal data held by a controller.

Because we hold **no personal data about you**, there is nothing for us to disclose, correct, export, or erase. You exercise these rights directly and immediately on your own device:

- **Access / portability** — your data is visible in the App; export functionality is provided in the App where available.
- **Correction** — edit or delete any record at any time inside the App.
- **Erasure** — deleting the App removes its local database from your device. If iCloud sync was enabled, you can additionally remove the App's iCloud data in iOS Settings → your Apple Account → iCloud → Manage Account Storage.

We do not sell or share personal information, and we do not engage in "targeted advertising" or "profiling" as defined by applicable privacy law.

## 10. Data Security

Your data is protected by iOS's built-in application sandbox and, when your device is locked with a passcode, by full-device encryption. iCloud data is encrypted in transit and at rest by Apple. You can enable an additional Face ID / Touch ID / passcode lock inside MoneyFlux.

Because your data never leaves your control, there is no central database of MoneyFlux users that could be breached. However, no method of electronic storage is completely secure, and you are responsible for keeping your device and Apple Account secure.

## 11. Data Retention

We retain nothing, because we receive nothing. Your data persists on your device (and, if enabled, in your iCloud account) until you delete it or uninstall the App.

## 12. International Transfers

Since no data is transmitted to us, there are no international transfers of your personal data by the Developer. Any transfer performed by Apple as part of iCloud sync is governed by Apple's terms.

## 13. Changes to This Policy

We may update this Privacy Policy from time to time — for example, if new features change how data is handled. The updated version will be posted on this page with a revised "Last updated" date. Material changes will additionally be announced in the App's release notes. Continued use of the App after an update constitutes acceptance of the revised Policy.

## 14. Contact

Questions about this Privacy Policy or about MoneyFlux's data practices:

**Taras Chernysh**
Independent developer, Ukraine
Email: **chernyshtaras94@gmail.com**

We aim to respond to all enquiries within 30 days.
