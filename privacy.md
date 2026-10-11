---
title: Privacy Policy
---

# Infra Pulse — Privacy Policy

_Last updated: 11 October 2026_

Infra Pulse is a read-only status dashboard for your own website's services.
It is built so that we never see your data.

## What we collect

**Nothing.** Infra Pulse has no accounts, no backend server, no analytics,
no advertising and no crash-reporting SDK. The developer receives no data
about you or your use of the app.

## What stays on your device

- **API keys and your domain name** that you enter are stored only on your
  device, in the iOS Keychain or Android Keystore, marked "this device only"
  so they are not synced to iCloud or restored onto another device.
- **Dashboard data** is kept in memory while the app runs and is not written
  to disk.
- Removing the app, or **Settings → Remove all keys and reset**, deletes
  everything the app stored.

## Who the app talks to

The app connects directly from your device to:

| Service | Why | Sent |
|---|---|---|
| Vercel, Render, GoDaddy, UptimeRobot (only those you connect) | read your deployments, services, DNS records, monitors | the API key you entered for that service |
| rdap.org and your domain's registry | domain expiry date (public registration data) | your domain name |
| Cloudflare DNS (cloudflare-dns.com) | public DNS records | your domain name |
| Your own website (port 443) | SSL certificate expiry | a standard TLS connection |

Each key is sent only to the service it belongs to. These services' own
privacy policies apply to those requests. The app only ever reads data; it
never changes anything in your accounts.

## Face ID / fingerprint

If you turn on the app lock, the operating system checks your face or
fingerprint. The app only receives "succeeded" or "failed"; biometric data
never leaves the system.

## Children

Infra Pulse is a tool for website owners and is not directed at children.

## Changes and contact

Changes to this policy will be published at this address with a new date.
Questions: boraunofficial@gmail.com

[← Infra Pulse](./)
