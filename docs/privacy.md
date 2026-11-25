# Privacy Policy for AI Chat Exporter & Organizer: Claude, ChatGPT, Gemini and Grok

**Effective date: November 25, 2026**

AI Chat Exporter & Organizer ("the extension", "we", "us") is a browser extension that
exports conversations from ChatGPT, Claude, Gemini and Grok. This policy explains what the
extension does with your data, where it is stored, who it is shared with, and how you can
control it.

## Summary

- Exporting, copying, PDF, Word, Markdown, JSON, text, the table of contents and message
  selection work **without an account**, and your conversation content is processed inside
  your browser and never sent to us.
- Signing in is optional and is only needed for the paid features: tags, folders and
  bookmarks. Signing in sends **account and subscription metadata** to our backend. It does
  **not** send your conversations, tags, folders or bookmarks.
- We do not sell your data, run ads, use analytics, or track your browsing.

## Who we are

The data controller is KavKrish Apps (Subin Mohan Kumar), 366 Alagesan Road, S. B. Mission
Post, Saibaba Colony, Coimbatore, Tamil Nadu 641011, India.

Privacy contact: **aichatexporter@kavkrishapps.in**. You can also open an issue at
[github.com/kavkrishapps/aichatexporter](https://github.com/kavkrishapps/aichatexporter).

## Data processed on your device (no account required)

The extension reads the conversation you ask it to export from the page you are already
viewing on one of these sites:

- `chatgpt.com`
- `claude.ai`
- `gemini.google.com`
- `grok.com`

It builds the export in your browser and writes it to your clipboard or a local file. To read
a conversation, the extension may call the same site's own API using the session you are
already signed in to. Those requests go to that AI site, not to us.

The following stay in your browser's extension storage and are **not uploaded**:

- tags, folders and bookmarks
- export settings and preferences
- table-of-contents and UI state

The extension does not set cookies, and it does not read pages other than the four sites
listed above.

## Data we collect only if you sign in

Signing in is optional. It unlocks tags, folders and bookmarks (Plus). You can sign in with
Google or with an email address and password. If you sign in, we store the following on our
backend:

| Data | Why |
|------|-----|
| Account identifier (Google `sub`, or a generated id for email/password accounts) | To recognise your account. Google accounts are keyed on the stable Google identifier, not the email address. |
| Email address | To identify your account, sign in with email/password, and send a password-reset link when you ask for one. |
| Display name and profile picture URL | Shown in the extension's account panel. The name is optional for email/password accounts; Google supplies both. |
| Password hash (email/password accounts only) | To check your password at sign-in. Stored as a PBKDF2-HMAC-SHA256 hash with a random salt and 600,000 iterations. We never store or receive your plaintext password, and the hash is never sent back to the extension. |
| Random session token | Kept in your browser's local extension storage and sent with each request instead of your password. It expires after 90 days, or immediately when you sign out or reset your password. |
| Subscription plan, status, currency, amount and current period end | To decide whether the paid features are unlocked. |
| Payment-provider subscription and payer identifiers | To match your subscription to your account and to process cancellations and renewals. |
| Password-reset token hash and expiry | To validate a single-use reset link. We store only a SHA-256 hash of the token, never the token itself. |
| Sign-in and reset throttling counters | To limit brute-force and email-bombing attempts. The counters are keyed by email address and are kept for one day. |
| Payment webhook records | To make payment processing idempotent and to investigate billing problems. The raw event may contain the payer's email address. |

We do **not** upload your conversations, conversation titles, conversation URLs,
tags, folders, bookmarks, browsing history, health data, location data, or keystroke and
mouse activity.

Like any web service, our backend receives standard request metadata such as IP address, user
agent and timestamps. We use it only for security, abuse prevention and debugging, not for
analytics or advertising, and it is retained under our hosting provider's normal log settings.

## How we use your data

We use the data above only to:

- authenticate you and keep you signed in;
- check whether your Plus subscription is active;
- send a password-reset link when you request one;
- process subscriptions, cancellations and renewals through PayPal;
- prevent abuse of the sign-in and password-reset endpoints;
- answer support requests you send us.

We do not use your data for advertising, profiling, analytics, or any purpose unrelated to
the extension's single purpose of exporting and organising AI conversations. We do not sell
your data. Our use of user data is limited to the extension's single purpose and the purposes
listed above, and we do not use it to determine creditworthiness or for lending purposes.

## Legal bases (EEA and UK users)

Where the GDPR or UK GDPR applies, we rely on:

- **performance of a contract**, to provide the account and subscription you asked for;
- **legitimate interests**, to keep the service secure and prevent abuse;
- **legal obligation**, where we must keep records for tax or accounting purposes.

You can stop using the account and sign out at any time. Where we rely on consent, you can
withdraw it at any time; this does not affect processing that already happened.

## Where data is stored and how long we keep it

Our backend is hosted by [Convex](https://convex.dev). Account, session, entitlement and
payment metadata are stored there. Your browser stores the session token, settings, tags,
folders and bookmarks locally.

| Data | Retention |
|------|-----------|
| Session tokens | 90 days from issue, or until you sign out. A password reset revokes every session immediately. |
| Password-reset links | Expire after 30 minutes, work once, and are pruned daily. |
| Sign-in and reset throttling counters | Kept for one day, then deleted. |
| Payment webhook records | Deleted 90 days after receipt. |
| Abandoned checkouts | Deleted 30 days after they are started. |
| Account and subscription records | Kept while your account exists. You can ask us to delete them. |

If you are outside the country where our service providers operate, your data may be
transferred to and processed in those countries. We use the providers named below and take
reasonable steps to protect data during those transfers.

## Who we share data with

We share data only with service providers that help us run the extension:

- **Convex** hosts our backend and stores account, session, entitlement and payment metadata.
- **Resend** delivers password-reset emails. It receives your email address and the reset
  message.
- **PayPal** processes subscriptions and payments. Payment details such as card or bank
  numbers are entered on PayPal's site and never reach us. We receive subscription and payer
  identifiers, subscription status, currency, amount, period end, and, when PayPal includes it
  in a webhook, the payer's email address. PayPal's own privacy policy applies to PayPal's
  processing.
- **Google** provides Google sign-in. When you choose Google sign-in, Google sends us your
  account identifier, email address, display name and profile picture URL.
- **UserJot** hosts our optional feedback board. The extension only opens a link to it. If you
  choose to submit feedback there, the information you enter is handled by UserJot under its
  own privacy policy.

We do not sell, rent, or trade your data. We do not share it with advertisers, data brokers,
or analytics providers.

## Google API Services

Our use of information received from Google APIs adheres to the
[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
including the Limited Use requirements. We use Google user data only to sign you in and show
your account in the extension. We do not transfer it to third parties except as needed to
provide the extension, and we do not use it for advertising or to determine creditworthiness.

## Permissions the extension requests

| Permission | Purpose |
|------------|---------|
| `storage` | Save your settings, tags, folders, bookmarks and local session token. |
| `identity` | Open Google's sign-in page so you can sign in without sharing your Google password with us. Email/password sign-in does not use this permission. |
| Host permissions for `*.convex.site` and `*.convex.cloud` | Reach our backend for sign-in, password reset and subscription checks. |
| Access to `chatgpt.com`, `claude.ai`, `gemini.google.com` and `grok.com` | Read the conversation you ask to export and show the export controls on those pages. |

## Your choices and rights

- **Use the extension without an account.** Exporting, copying, PDF, Word, Markdown, JSON and
  text do not require sign-in and do not send data to us.
- **Sign out** at any time from the account menu. This revokes your session.
- **Cancel a subscription** from the account menu, which links to PayPal's automatic-payments
  page, or directly in your PayPal account.
- **Clear local data** by removing the extension or clearing its storage in your browser. This
  removes tags, folders, bookmarks, settings and the local session token.
- **Access, correct, export or delete your account data** by emailing
  **aichatexporter@kavkrishapps.in**. We will delete your account record, sessions,
  entitlement and pending checkout. Payment webhook records are deleted on their normal
  90-day schedule. We may need to keep limited records where the law requires it.
- **Object or restrict processing**, or **lodge a complaint** with your local data-protection
  authority, where those rights apply to you.

## Security

- Data in transit uses HTTPS.
- Passwords are stored only as salted PBKDF2-HMAC-SHA256 hashes (600,000 iterations) and are
  compared in constant time. Plaintext passwords are never stored or logged.
- Password-reset tokens are stored only as SHA-256 hashes and are single-use.
- Session tokens are random and can be revoked by signing out or resetting your password.
- Payment card and bank details never reach our servers; they are entered on PayPal's site.
- All extension code ships inside the extension package. The extension does not download or
  execute remotely hosted code.

## Children

The extension is not directed at children under 13, and we do not knowingly collect data from
them. If you believe a child has created an account, email us and we will delete it.

## Changes to this policy

If this policy changes, we will update the effective date at the top of this page. Material
changes will be reflected here before they take effect.

## Contact

KavKrish Apps
366 Alagesan Road, S. B. Mission Post, Saibaba Colony
Coimbatore, Tamil Nadu 641011, India

Email: **aichatexporter@kavkrishapps.in**

GitHub: [github.com/kavkrishapps/aichatexporter](https://github.com/kavkrishapps/aichatexporter)

## Affiliation

AI Chat Exporter & Organizer is an independent tool and is not affiliated with, endorsed by,
or connected to OpenAI, Google, xAI, Anthropic, or PayPal.
