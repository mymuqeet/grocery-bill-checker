---
layout: default
title: "Privacy Policy - Grocery Bill Checker"
---

# Privacy Policy for Grocery Bill Checker

<div class="meta">
  <strong>Last Updated:</strong> August 21, 2026 &nbsp;|&nbsp;
  <strong>Version:</strong> 1.0 &nbsp;|&nbsp;
  <strong>Contact:</strong> <a href="mailto:mymuqeet@gmail.com">mymuqeet@gmail.com</a>
</div>

---

## 📱 Introduction

**Grocery Bill Checker** ("we," "our," or "the App") is committed to protecting your privacy. This Privacy Policy explains how we handle your information when you use our Android application.

> **Key Principle:** Your data stays on your device. We do not collect, transmit, or store any personal information on external servers.

---

## 📊 Information We Collect

### ✅ Data Stored Locally on Your Device

The following data is stored **only on your device** using Android's encrypted storage:

| Category | Details |
|----------|---------|
| **Shopping Data** | Product names, quantities, prices, categories, discounts, notes |
| **Shopping Sessions** | Session names, dates, calculated totals, store names |
| **Favorites** | Product names, default prices, categories |
| **Budgets** | Monthly budget amounts, spending limits |
| **Price History** | Product names, prices, store names (for price tracking) |
| **App Preferences** | Currency, language, theme (dark/light), tax percentage |
| **Security Settings** | App lock PIN (encrypted), biometric preference |
| **Bill Proof Records** | Comparison results, trust scores, mismatch details |

### ❌ Data We Do NOT Collect

- Personal identifiers (name, email, phone, contacts)
- Location data (GPS, network location)
- Account credentials or authentication tokens
- Device identifiers (IMEI, Android ID, advertising ID — except as noted below)
- Photos or media from your gallery
- Microphone or audio data
- Call logs or SMS messages

---

## ⚙️ How We Use Your Data

All data processing occurs **locally on your device**. We use your data solely to:

- Calculate shopping totals in real-time
- Compare your calculated totals with store bills
- Track price history for your favorite products
- Provide spending statistics and insights
- Enable budget planning and alerts
- Secure the app with PIN/biometric lock
- Backup and restore your data (user-initiated)

> **We do not use your data for:** advertising profiling, analytics, marketing, or any commercial purpose beyond the app's core functionality.

---

## 🌐 Third-Party Services

### Google AdMob (Advertising)

The free version of the app displays ads via **Google AdMob**.

**What AdMob may collect:**
- Advertising ID (resettable in Android Settings → Google → Ads)
- IP address (for ad delivery)
- General location (country-level, from IP)
- App interaction data (ad impressions, clicks)

**AdMob does NOT receive:** Your shopping data, personal information, or any app-specific content.

**Opt-out options:**
- Android Settings → Google → Ads → "Opt out of Ads Personalization"
- Reset Advertising ID in the same menu
- Upgrade to Premium (removes ads entirely)

[AdMob Privacy Policy](https://policies.google.com/technologies/ads)

### Google Play Services

Required for AdMob functionality and license verification (if Premium).

### ML Kit (On-Device)

Used for **barcode scanning** and **text recognition (OCR)**.

- All processing happens **on-device**
- No images or data sent to Google servers
- Models downloaded at install time

---

## 🔒 Data Storage & Security

| Protection | Implementation |
|------------|----------------|
| **At Rest** | Room Database + EncryptedSharedPreferences (AES-256-GCM) |
| **In Transit** | HTTPS only (Network Security Config: `cleartextTrafficPermitted=false`) |
| **Backup** | User-controlled JSON export/import via system file picker |
| **Cloud Sync** | None — no cloud backup, no account system |
| **Access Control** | Optional PIN + Biometric (fingerprint/face) app lock |

---

## 🛡️ Your Rights & Controls

You have full control over your data:

| Action | How to Access |
|--------|---------------|
| **View all data** | App screens: Home, History, Favorites, Budget, Bill Proof |
| **Export data** | Settings → Backup Data (JSON) / Export PDF / Export Excel |
| **Delete specific items** | Swipe to delete in Cart, History, Favorites |
| **Delete all shopping data** | Settings → Danger Zone → Delete Shopping Data |
| **Reset app completely** | Android Settings → Apps → Grocery Bill Checker → Clear Data |
| **Disable ads** | Upgrade to Premium (in-app purchase) |
| **Opt-out of ad personalization** | Android Settings → Google → Ads |

---

## 👶 Children's Privacy

The App is not directed to children under 13 (or applicable age in your jurisdiction). We do not knowingly collect personal information from children. If you believe a child has provided personal information, contact us immediately.

---

## 📅 Data Retention

- **Local data:** Retained until you delete it or uninstall the app
- **AdMob data:** Governed by Google's retention policies (see [AdMob Privacy Policy](https://policies.google.com/technologies/ads))
- **No server-side retention** — we operate no servers

---

## 🌍 International Transfers

Since we do not operate servers or transfer data internationally, no cross-border data transfers occur. AdMob (Google) may process data globally per their privacy policy.

---

## 🔄 Changes to This Policy

We may update this policy for:

- Legal/regulatory changes
- New app features
- Clarity improvements

**Notification:** Updates posted here with new "Last Updated" date. Material changes notified in-app.

---

## ⚖️ Legal Basis (GDPR/UK DPA)

As we process **no personal data on our servers**, GDPR controller obligations do not apply to us. For AdMob processing, Google acts as independent controller.

---

## 🇺🇸 California Privacy Rights (CCPA/CPRA)

We do not "sell" or "share" personal information as defined by CCPA. No personal information collected → no deletion/access requests applicable to us.

---

## 📞 Contact Us

| Detail | Information |
|--------|-------------|
| **Email** | <a href="mailto:mymuqeet@gmail.com">mymuqeet@gmail.com</a> |
| **App** | Grocery Bill Checker (`com.simitech.grocerybillchecker`) |
| **Developer** | mymuqeet |

---

## 📁 GitHub Repository

Source code and this policy: [github.com/mymuqeet/grocery-bill-checker](https://github.com/mymuqeet/grocery-bill-checker)

---

*This policy is effective as of the "Last Updated" date above.*

<style>
  .meta { color: #666; font-size: 0.9rem; margin-bottom: 1.5rem; padding-bottom: 1rem; border-bottom: 1px solid #eee; }
  table { width: 100%; border-collapse: collapse; margin: 1rem 0; }
  th, td { padding: 0.75rem; text-align: left; border-bottom: 1px solid #eee; }
  th { background: #f6f8fa; font-weight: 600; }
  tr:hover { background: #fafbfc; }
  blockquote { border-left: 4px solid #0366d6; padding-left: 1rem; color: #666; margin: 1rem 0; }
  h1 { border-bottom: 2px solid #eee; padding-bottom: 0.5rem; }
  h2 { border-bottom: 1px solid #eee; padding-bottom: 0.3rem; margin-top: 2rem; }
  h3 { margin-top: 1.5rem; }
  code { background: #f6f8fa; padding: 0.2rem 0.4rem; border-radius: 3px; font-size: 0.9em; }
  a { color: #0366d6; text-decoration: none; }
  a:hover { text-decoration: underline; }
  ul { line-height: 1.8; }
</style>
