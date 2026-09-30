---
layout: page
title: Privacy Policy
permalink: privacy-policy-formly/
---

# Privacy Policy for Formly

**Effective date:** September 30, 2026

This Privacy Policy explains how **Formly** (the "Extension"), operated by LobCode s.r.o. ("we", "us", "the developer"), handles information.

The Extension reads the file you upload and the form on the page you're viewing, sends that information to an AI provider to determine what to fill in, and writes the result back into the form. The Extension's own backend does not store the content of your files.

---

## Summary

- The Extension **sends the content of files you upload, and the form fields on the page you're filling**, to a third-party AI provider (OpenAI and/or Anthropic) solely to determine what to fill into the form.
- The Extension's own backend **does not store the content of your uploaded files or the values extracted from them**.
- The Extension stores a small amount of data **locally, on your device** (an anonymous install id, and — to let you reopen the popup without re-uploading — the result of the last file you processed on the current page).
- The Extension's backend stores a limited amount of account-linking and usage-count data (an anonymous device fingerprint/install id, and how many fills you've used this month) to enforce the free/paid usage limits.
- The Extension has **optional paid plans**, handled by our payment processor, ExtensionPay (extensionpay.com), via Stripe. We do not directly handle or store your payment card details.
- The Extension does **not** collect your browsing history, location, passwords, health information, or personal communications, and does not track your activity (clicks, keystrokes, mouse movement) on any page.

---

## How the Extension Works

When you click the Formly icon and upload a file (PDF, Word, Excel, CSV, or an image):

1. The Extension reads the fillable fields (and their labels) on the web page you're currently viewing.
2. The content of your uploaded file, together with the list of form fields, is sent to Formly's backend, which forwards it to an AI provider (OpenAI and/or Anthropic) to determine the value for each field.
3. The AI's response is written back into the form's fields on the page, only after you click "Fill form".

This processing:

- Is only triggered when you actively upload a file and click the extension icon — the Extension does not read pages in the background.
- Sends the file's content and the page's field labels to the AI provider **only to generate that one response** — not for any other purpose.
- Is not used to build a profile of you, track you across websites, or serve ads.

---

## What Is Sent to Third Parties

| Data | Sent to | Purpose |
|---|---|---|
| Content of the file you upload, and the target form's field labels | OpenAI and/or Anthropic (AI providers) | To determine the value to fill into each field |
| Anonymous device fingerprint and install id | Formly's own backend (Cloudflare Workers) | To enforce the free-tier monthly usage limit and prevent abuse |
| Email address and subscription status (paid users only) | ExtensionPay (extensionpay.com) / Stripe | To process payment and verify your paid plan |

The Extension's own backend relays your file to the AI provider and returns its response — it does not keep a copy of your file's content or the extracted values. Data sent to the AI provider is subject to that provider's own data handling and retention practices; Formly does not control how long the AI provider itself retains API request data.

---

## Local Data Storage

The Extension stores the following locally, in your browser's extension storage:

- A randomly generated, anonymous install id
- The result of the last file you processed on the current page (so reopening the popup doesn't require re-uploading the file) — this can include the values extracted from your file

This data:

- Remains on your device / in your browser profile
- Is not transmitted to the developer, except for the anonymous install id, which is sent with each request purely to look up your usage count
- Can be removed by clicking "Forget this file" in the Extension, or by clearing the Extension's storage / uninstalling the Extension

---

## Data Stored on Our Backend

To enforce the free (10/month) and paid usage limits, Formly's backend stores:

- An anonymous device fingerprint and install id, linked to an account key
- For paid users, the email address associated with your ExtensionPay subscription
- A monthly count of how many times you've used the Extension

This data does **not** include the content of any file you've uploaded, or any values extracted from it — only what's needed to enforce usage limits.

---

## Data Sharing

The developer does not sell or rent user data. Data is only shared with the service providers necessary to deliver the Extension's functionality:

- **OpenAI / Anthropic** — to process the file you upload and determine form field values
- **ExtensionPay / Stripe** — to process optional paid subscriptions

No data is shared with any other third party, and no data is used for advertising, credit/lending decisions, or any purpose unrelated to the Extension's single purpose of filling a form from an uploaded file.

---

## Children's Privacy

The Extension does not knowingly collect personal data from children. The Extension requires no account for the free tier, and any file you choose to upload and any web page you choose to use it on is entirely user-initiated.

---

## EU Users (GDPR)

If you are located in the European Union, you have rights under the General Data Protection Regulation (GDPR), including:

- The right to access your personal data
- The right to request correction or deletion
- The right to restrict or object to processing

The personal data we hold is limited to what's described above (an anonymous fingerprint/install id, usage counts, and — for paid users — the email tied to your subscription). We do not retain the content of files you upload. To exercise these rights, contact us at the address below; for billing/subscription data, you can also manage or delete your account directly through ExtensionPay.

---

## Data Retention

- **File content and extracted values:** not retained by Formly's backend — it is relayed to the AI provider and the response returned to you, with nothing stored server-side.
- **Anonymous fingerprint/install id and usage counts:** retained for as long as needed to enforce monthly usage limits, or until you request deletion.
- **Local data on your device** (session cache, install id): remains until you clear it via the Extension's "Forget this file" option, clear the Extension's storage, or uninstall the Extension.

---

## Changes to This Policy

This Privacy Policy may be updated from time to time.
When updated, the "Effective date" above will be revised.

---

## Contact

If you have any questions about this Privacy Policy, you may contact:

**LobCode s.r.o.**
**Email:** csv.filler@gmail.com
