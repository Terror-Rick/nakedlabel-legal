Here it is — ready to host:

---

# Privacy Policy

**App:** NakedLabel
**Developer:** Skyler Daniel
**Effective Date:** [EFFECTIVE_DATE]

---

## Overview

NakedLabel helps you make informed choices about the products you buy by scanning barcodes and analyzing ingredient lists. This policy explains what data the app collects, why it collects it, and how it is handled.

The short version: NakedLabel does not sell your data, does not store photos, and does not collect your location. Most data stays on your device.

---

## 1. Who This Policy Applies To

This policy applies to all users of the NakedLabel Android app. An iOS version is planned and will be covered by this same policy when released.

---

## 2. Data We Collect and Why

### 2.1 Camera Access
NakedLabel requests access to your device camera **solely to scan barcodes**. The camera is activated only when you initiate a scan. No photos or images are captured, stored, or transmitted — the app reads only the barcode value.

### 2.2 Account and Identity
NakedLabel uses **Firebase Anonymous Authentication** to give you a persistent experience without requiring you to create an account. When you first open the app, Firebase automatically generates an anonymous, randomly assigned user ID. This ID has no connection to your name, email, or any other identifying information.

If you choose to upgrade to a premium subscription, you may optionally sign in with **Google Sign-In**. You are never required to create an account to use core features.

### 2.3 Scan History and Product Data
- **On your device** (local database): barcodes scanned and grading results.
- **In Firebase Firestore** (under your anonymous UID): product grading results cached for instant repeat scans.

You can delete your scan history at any time from within the app.

### 2.4 Ingredient Analysis
Ingredient names are sent to **Google Gemini AI** via secure Firebase Cloud Functions for health grading. No personal information is included in these requests. Cached grading results are not linked to any individual user.

### 2.5 In-App Purchases
**RevenueCat** manages subscriptions and processes purchase receipts. NakedLabel receives only your subscription status — never your payment details. See [RevenueCat's Privacy Policy](https://www.revenuecat.com/privacy).

### 2.6 Analytics and Crash Reporting
**Firebase Analytics** and **Crashlytics** collect anonymous, aggregated usage and crash data (device model, OS version, stack traces) to improve stability. No personally identifiable information is included.

### 2.7 What We Do Not Collect
- Location data
- Photos or images
- Contacts or messages
- Payment card information

---

## 3. Third-Party Services

| Service | Purpose | Privacy Policy |
|---|---|---|
| Google Firebase | Auth, database, cloud functions, analytics, crash reporting | [firebase.google.com/support/privacy](https://firebase.google.com/support/privacy) |
| Google Gemini AI | Ingredient health grading | [ai.google.dev/terms](https://ai.google.dev/terms) |
| RevenueCat | Purchases and subscriptions | [revenuecat.com/privacy](https://www.revenuecat.com/privacy) |
| Open Food Facts | Public product database | [world.openfoodfacts.org/privacy](https://world.openfoodfacts.org/privacy) |
| USDA FoodData Central | Public nutrient database | [fdc.nal.usda.gov](https://fdc.nal.usda.gov/) |

NakedLabel does not sell, rent, or share your data with any third party for advertising or marketing purposes.

---

## 4. Data Storage and Security
All Firebase data is restricted by security rules to your authenticated UID. All transmissions are encrypted via HTTPS/TLS. Firebase App Check verifies requests originate from the legitimate NakedLabel app.

---

## 5. Your Rights and Choices
- **Delete scan history:** Available anytime in app settings.
- **Request data deletion:** Email [YOUR_EMAIL] with your anonymous UID (found in app settings). We will delete within 30 days.
- **Google Sign-In users:** Revoke access via [Google Account Settings](https://myaccount.google.com/permissions).

---

## 6. Children's Privacy
NakedLabel is not directed at children under 13. We do not knowingly collect information from children under 13. Contact [YOUR_EMAIL] to report any concerns.

---

## 7. Changes to This Policy
When changes are made, the Effective Date will be updated. Continued use after changes take effect constitutes acceptance.

---

## 8. Contact

**Skyler Daniel**
Email: [YOUR_EMAIL]
Response time: within 30 days.

---

**To publish:** Replace `[YOUR_EMAIL]` and `[EFFECTIVE_DATE]`, paste into a GitHub Pages file, Notion public page, or Google Sites — then use that URL in Play Console.
