---
layout: default
title: MapThat data-deletion instructions
description: How to request deletion of personal data held by MapThat.
---

# Data-deletion instructions

**Effective date: 10 October 2026**

To request deletion of personal data held by MapThat, email
[appmapthat@gmail.com](mailto:appmapthat@gmail.com) with the subject
**MapThat data deletion**.

Include your Instagram username and describe the MapThat conversation or contact
request concerned. You can include the approximate date of your interaction to
help locate it. Do not include passwords, access tokens, or a copy of your entire
private conversation. We may ask for limited confirmation that the request
concerns your account.

Martin Janus, the operator of MapThat, handles these requests manually. We will
review the information we hold, delete personal data that can be deleted under
applicable law, and explain the outcome or any required retention. Where the
GDPR applies, its response deadlines and permitted exceptions apply; the normal
response period is one month from receipt of a request.

## What the current prototype holds

- Message content is processed temporarily in memory; there is no application
  database or persistent message archive.
- Duplicate-prevention records expire after 36 hours and are removed during the
  next webhook-processing pass, or when the process restarts. They contain the
  MapThat account identifier, message identifier, and expiry time, not message
  text or sender identifiers.
- Messages and replies may remain in the MapThat Instagram inbox, and privacy or
  support emails may remain in the contact mailbox. Please identify those when
  making a deletion request.
- Operational logs contain aggregate outcomes rather than private message
  content or Instagram identifiers.

Deletion from MapThat does not guarantee deletion of copies held independently
by Meta, your own Instagram account, or other providers. For those copies, use
the provider's account controls or contact the provider directly. If you linked
an Instagram account to the app, remove MapThat in Instagram's Apps and websites
settings to revoke future access.

For more information, read the [privacy policy](privacy.html).

[MapThat public information](index.html) · [Privacy policy](privacy.html)
