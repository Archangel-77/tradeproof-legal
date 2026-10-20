---
title: Privacy Policy — TradeProof
description: How the TradeProof Android app handles your data: everything stays on your device.
---

# Privacy Policy — TradeProof

**Effective date:** 20 October 2026
**Applies to:** the Android app **TradeProof** (package `io.github.archangel77.tradeproof`)

**Developer:** [YOUR NAME OR BUSINESS NAME] ("we")
**Contact:** tradeproof.app.support@gmail.com

---

## The short version

TradeProof keeps your documents on your phone. There is no account, no server of ours, and no
upload of your receipts, clients or invoices. The only times data leaves the device are when
**you** share an invoice, and when Google's libraries used for purchases and on-device text
recognition send their own operational diagnostics.

## What the app stores, and where

Everything below is stored **only in the app's private storage on your device**:

- photographs you take or select, and the text read from them;
- the values you confirm from a receipt (vendor, date, amounts, VAT rate, line items);
- your clients' names, addresses and e-mail addresses, if you enter them;
- your business details and, if you add them, your IBAN, account holder and logo;
- jobs, line items and generated invoice PDFs;
- the subscription status Google Play reports to the app.

We have no servers, no user accounts and no way to read this data. Uninstalling the app deletes
all of it, and deleting a job or a document inside the app deletes the stored files too.

## Permissions

- **Camera** — used only to photograph receipts and work orders. Images are saved in app-private
  storage and are never uploaded by us.
- A logo is chosen through Android's **system photo picker**, which gives the app only the image
  you pick. No broad storage permission is requested.
- The app does **not** request location, contacts, microphone, calendar, phone state or
  advertising identifiers.

## When data leaves the device

1. **Sharing an invoice.** When you tap Share, the app hands the generated PDF to Android's share
   sheet. Where it goes is your choice; once it reaches another app or service, that recipient's
   own privacy terms apply.
2. **Purchases.** Subscriptions are processed by **Google Play Billing**. Google handles your
   payment details — the app never sees them — and tells the app whether a subscription is
   active.
3. **SDK diagnostics.** The app uses two Google libraries: Play Billing (purchases) and ML Kit
   text recognition (which reads receipts **on the device**). These libraries include Google's
   Data Transport component, which may send operational diagnostics to Google — for example app
   and device information and error reports — as described in Google's privacy policy
   (https://policies.google.com/privacy). This happens even though our own code makes no network
   calls. We do not receive, store or use that data, and the contents of your documents are not
   part of it.

We do not use analytics, advertising, crash-reporting or attribution SDKs of our own. We do not
sell data. We do not profile you.

## Children

TradeProof is a business tool intended for adults. It is not directed to children, and we do not
knowingly collect information from children.

## Your rights

Because the data lives only on your device, we hold nothing that we could export, correct or
erase for you. You exercise these rights directly:

- **Access and portability** — everything is visible in the app; invoices can be shared as PDFs.
- **Erasure** — delete individual jobs or documents in the app, or uninstall the app to remove
  everything.
- **Withdrawal of consent** — revoke the camera permission in Android settings at any time; the
  app then offers manual entry instead.

If you believe we hold something about you anyway, write to the contact address above and we will
answer within 30 days.

## Data retention

Nothing is retained by us. On your device, data stays until you delete it or uninstall the app.

## Changes

If this policy changes, the new version is published at this address with a new effective date.
Material changes affecting how existing data is handled will also be noted in the app's release
notes.

## Governing law

This policy is governed by the laws of [YOUR COUNTRY / JURISDICTION], without regard to conflict
of law rules.

---

*This document describes the behaviour of the released app. It was written from the app's code
and its audited permission set, not from boilerplate; it is not legal advice.*
