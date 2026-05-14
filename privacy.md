---
layout: default
title: Privacy Policy
---

# FlashFocus Privacy Policy

**Effective date:** May 9, 2026

FlashFocus ("we", "us", "our") is a study app published by codebynaci. This Privacy Policy explains what information we collect, how we use it, and the choices you have. It applies to the FlashFocus mobile app on iOS and Android and to the supporting backend services we operate.

You can study, create your own decks, and review them with spaced repetition **without an account**. An account is only required for features that need a server — AI assistance, paid Flash Credits, the Pro subscription, marketplace purchases, and account-tied progress recovery.

---

## 1. Information We Collect

### 1.1 Account Information

If you create an account, we collect:

- Full name
- Email address
- Date of birth (used to enforce the 13+ minimum age)
- Password (stored as a salted hash; we never see the plaintext)
- Profile photo, if you upload one

If you sign in with **Google** or **Apple**, we receive your name, email, and the provider's stable user identifier (the `sub` claim) instead of a password. We verify these tokens server-side and issue our own session token; we do not store your Google or Apple password.

### 1.2 Study Content & Activity

- Decks and cards you create or save, including any text, images, or audio you attach
- Study sessions (which decks you studied, when, how many cards, accuracy)
- Spaced-repetition state (each card's interval, ease factor, next-review date)
- Streaks, weekly goals, achievements, and XP earned
- Exam-mode attempt history (score, time taken, per-subject breakdown)
- Head-to-head challenge results, if you participate

For users without an account, this information stays on your device only.

### 1.3 Flash Credits & Purchases

- Flash Credits balance and transaction history (signup bonus, monthly refresh, AI spend, referral, in-app purchase, subscription)
- Subscription status (active, expired, in grace period) supplied to us by **RevenueCat**
- The receipt identifier returned by the Apple App Store or Google Play after a purchase

We do **not** receive your full payment-card or banking details. The Apple App Store and Google Play handle those directly; we only see that a purchase succeeded for a specific product.

### 1.4 Device & Technical Data

- Device model, operating system version, app version, locale, time zone
- A push-notification token issued by **Firebase Cloud Messaging** (only if you grant notification permission)
- IP address (visible to our servers when you make a request; used for security and rate limiting; not stored long-term as a profile attribute)

### 1.5 AI Interactions

When you use an AI feature (deck generation, "Explain this card", chat with a deck, weak-spot analysis), the relevant prompt content is sent through our backend to **OpenAI** so the model can answer it. That content can include:

- The card question, answer, and any explanation you tap to expand
- The deck title, description, and the cards we send as study context
- Any document text, image, or URL you submit to "Create from document"
- Your messages in a chat session

We do not send your name, email, or password to OpenAI. We send a backend-generated user identifier so OpenAI can apply per-user abuse protection. OpenAI does not use API content sent through our backend to train its models.

### 1.6 Crash Reports

We do not currently ship a third-party crash reporter in the mobile app. If we add one before submission, we will update this policy and disclose it in the App Privacy / Data Safety listings on each store.

---

## 2. How We Use Your Information

- **Provide the service** — deliver decks, run spaced-repetition scheduling, save study progress, process purchases, route AI requests
- **Personalise** — adapt the home screen using your survey answers, suggest categories, time push reminders to your preferred study windows
- **Communicate** — email you about your account (verification, password resets), respond to your support requests, send streak / due-card push notifications you have opted into
- **Protect the service** — detect abuse of Flash Credits, AI features, and referrals; investigate security incidents
- **Improve the app** — debug specific issues you report and aggregate study data to inform feature decisions

We do not sell your personal data. We do not run third-party advertising in v2.0.0 — there is no ad network or tracking SDK in the app.

---

## 3. How We Share Information

We share information only with the third parties listed below, only for the purposes described.

| Provider | What we share | Why |
|---|---|---|
| **OpenAI** | Prompt content for AI features (see §1.5) | Run AI-generated decks, explanations, chat, weak-spot analysis |
| **RevenueCat** | Purchase / subscription events + your account user ID | Manage subscription state across devices and stores |
| **Apple App Store / Google Play** | Receipt identifiers for verification | Process and validate in-app purchases |
| **Google Sign-In / Apple Sign-In** | OAuth tokens you grant at sign-in | Authenticate you without a password |
| **Firebase Cloud Messaging (Google)** | Push notification tokens, message payloads | Deliver streak, due-card, and challenge notifications |
| **Amazon Web Services (S3)** | Deck cover images, profile photos, card media you upload | Store media so it can be downloaded on other devices |
| **SendGrid (Twilio)** | Email address + the email body | Send account, verification, and notification emails |

We may also disclose information when required by law or to protect users, our service, or the public from imminent harm.

---

## 4. Data Retention

We keep account data for as long as your account exists. When you delete your account (see §5), we erase or irreversibly anonymise your personal data within 30 days. Aggregated, non-identifying analytics (for example, "N decks generated this month") may be kept indefinitely.

Backups of our databases may persist for up to 90 days for disaster recovery before being overwritten.

---

## 5. Account Deletion & Data Export

You can manage your data directly in the app:

- **Delete my account** — `More → Security → Delete my account`. This permanently removes your profile, Flash Credits balance, subscription record, owned decks, study history, and AI usage history from our servers within 30 days, and clears the local database on the current device.
- **Download my data** — `More → Security → Download my data`. We email you a JSON archive of the data we hold about you.

If you cannot reach the in-app flow, email **info@minervaeduapp.com** and we will action the request manually.

Note: deleting your account does not automatically cancel an Apple or Google subscription — App Store and Play Store subscriptions must be cancelled in the device's subscription settings. We will release your account immediately on your request; the platform billing relationship is between you and the store.

---

## 6. Children's Privacy

FlashFocus accounts are for learners aged **13 and over**.

- No account is required to study; anyone, including users under 13, can use FlashFocus's local study features without registering or sharing personal information.
- You must be at least 13 years old to create a FlashFocus account. We collect a date of birth at signup specifically to enforce this minimum.
- We do not knowingly collect personal information from children under 13. If we learn that an account was created by a user under 13, we will delete it and any associated data.
- Parents or guardians who believe a child under 13 has created an account may email **info@minervaeduapp.com** to request immediate deletion.

---

## 7. International Data Transfers

Our infrastructure is hosted in regions including the United States, the European Union, and West Africa. By using FlashFocus, you consent to your information being transferred to and processed in those regions. We rely on standard contractual clauses or equivalent safeguards where required.

---

## 8. Security

We protect your data with HTTPS in transit, hashed passwords, scoped API access tokens, and role-based access to production systems. No system is perfectly secure; if we ever discover that your account data has been improperly accessed, we will notify you and the relevant authorities as required by law.

---

## 9. Your Rights

Depending on where you live, you may have the right to:

- **Access** — request a copy of the data we hold about you (use *Download my data*)
- **Correct** — fix inaccurate profile data (edit profile in-app or email us)
- **Delete** — permanently erase your data (use *Delete my account* or email us)
- **Restrict / object** — limit certain processing
- **Withdraw consent** — opt out of email or push communications at any time

To exercise these rights, use the in-app flows or email **info@minervaeduapp.com**. You also have the right to lodge a complaint with your local data protection authority.

---

## 10. Changes to This Policy

We may update this Privacy Policy when we change practices or add features that affect what we collect. When we make material changes, we will revise the **Effective date** above and notify you in-app or by email at least 30 days before the change takes effect, unless a shorter notice is required by law. Your continued use of FlashFocus after the effective date means you accept the updated policy.

---

## 11. Contact Us

For privacy questions, support, or to exercise any of the rights in §9:

**info@minervaeduapp.com**

codebynaci
