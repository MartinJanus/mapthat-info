---
layout: default
title: MapThat privacy policy
description: How the MapThat Instagram DM prototype processes personal data.
---

# Privacy policy

**Effective date: 10 October 2026**

## Who operates MapThat

MapThat is operated by **Martin Janus**. For privacy questions, personal-data
requests, or deletion requests, email
[appmapthat@gmail.com](mailto:appmapthat@gmail.com).

## What this version does

MapThat is an experimental Instagram DM service. The current version receives
ordinary text messages sent to its Instagram professional account and sends a
fixed acknowledgement through Meta's official API.

This version does not extract places from Reels, transcribe videos, send messages
to an AI provider, or create map results. This policy will be updated before
additional processing is introduced.

## Data we process

When you message MapThat, Meta may deliver your message text, Instagram-scoped
sender and recipient identifiers, message identifier, timestamp, and event
metadata to the service. A delivery can also include attachment information;
unsupported events and attachment messages are ignored by this version.

We use the sender identifier to address a reply. We temporarily process the
message and its metadata to check whether the event is supported, verify that it
came from Meta, and avoid reply loops or duplicate replies. We do not publish
private messages or use them for advertising or profile building.

If you contact us by email, we process your email address, the content of your
request, and information needed to respond or verify that the request concerns
your account. Do not send passwords, access tokens, or unrelated sensitive data.

## Why we process data

We process data to provide the message acknowledgement you request by contacting
MapThat, test the permitted messaging connection, prevent duplicate replies,
protect the service, and answer privacy or support requests. Providing a message
is voluntary; without the message and the identifier needed to reply, the
service cannot respond.

Where the GDPR applies, processing needed to provide the requested service is
based on Article 6(1)(b). Limited duplicate prevention, security, and service
operation rely on our legitimate interests under Article 6(1)(f). Responding to
statutory data-rights requests also supports compliance with legal obligations
under Article 6(1)(c).

## Storage and retention

The prototype has no application database or persistent message archive. Message
content is processed in memory while handling the delivery and is not written to
the application's operational logs. A controlled test may produce manually
redacted evidence with replaced identifiers and message text; it must not contain
private message content or identify a participant.

For duplicate prevention, the application keeps the MapThat account identifier,
message identifier, and expiry time in process memory. Entries expire after
36 hours and are removed during the next webhook-processing pass, or earlier
when the process restarts. The cache does not retain message text or sender
identifiers. Expiry is not a promise that every entry is erased precisely at the
36-hour mark.

Application logs contain event labels and aggregate outcome counts rather than
message bodies or Instagram identifiers. Hosting and network providers may
process technical connection data, including IP addresses, request timing, and
security information, under their own policies.

Messages and replies can remain in the MapThat Instagram inbox and in Meta's
systems. The application's memory policy does not erase those copies. Privacy
and support emails are retained while handling the request and necessary
follow-up, or where applicable legal obligations require retention.

## Services involved

- **Meta / Instagram:** supplies the messaging platform, delivers events, sends
  replies, and stores Instagram conversations under its own policies.
- **Cloudflare:** currently provides the HTTPS tunnel used to deliver webhook
  requests to the experimental service.
- **GitHub Pages:** hosts these public information pages. GitHub may process
  technical visitor information under its privacy statement.
- **Google / Gmail:** receives and stores email sent to our contact address.

These providers may process data in countries outside your own, including
outside the European Economic Area. Their processing and any applicable
international-transfer safeguards are described in their published policies:
[Meta](https://www.facebook.com/privacy/policy/),
[Cloudflare](https://www.cloudflare.com/privacypolicy/),
[GitHub](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement),
and [Google](https://policies.google.com/privacy).

We do not sell personal data. Disclosure may also be necessary to comply with a
legal obligation or protect the rights and security of the service and its users.

## This website

We do not add analytics, advertising trackers, tracking pixels, or contact forms
to these pages. Visiting them does not connect your Instagram account to MapThat.
The hosting provider still processes requests needed to serve the website.

## Your choices and rights

You can stop messaging MapThat at any time. If you connected an Instagram account
to the app, you can also remove the app's access in Instagram's Apps and websites
settings. Removing access does not automatically erase every existing inbox
message or support email.

Depending on the law that applies, you may have rights to access, correct, delete,
restrict, or receive a portable copy of your data, and to object to processing
based on legitimate interests. Contact
[appmapthat@gmail.com](mailto:appmapthat@gmail.com) to make a request. We may ask
for limited information to verify the account concerned. These rights may have
exceptions under applicable law.

You may also complain to the relevant data-protection authority. If you are in
the EEA, you can find your authority in the
[European Data Protection Board's directory](https://www.edpb.europa.eu/about-edpb/about-edpb/members_en).

See [data-deletion instructions](data-deletion.html) for how to request removal
of information held by MapThat.

## Changes and contact

The effective date above will change when this notice is updated. We will update
the notice before introducing materially different uses of personal data.

Contact: [appmapthat@gmail.com](mailto:appmapthat@gmail.com).

[MapThat public information](index.html) · [Data deletion](data-deletion.html)
