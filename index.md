---
title: Infra Pulse
---

# Infra Pulse

A read-only status dashboard for your website's services, on your phone:
uptime, deployments, domain and SSL certificate on one screen.

- **No account, no server in between.** The app talks to each service directly.
- **Your API keys stay on your device**, in the system keychain.
- **Read-only.** Infra Pulse never changes anything in your accounts.

[Privacy Policy](privacy)

## Support

Questions, problems or feedback: **[boraunofficial@gmail.com](mailto:boraunofficial@gmail.com)**

Please tell us your phone model and what you were doing when the problem
happened. **Never send your API keys** — we will never ask for them.

### Common questions

**How do I connect a service?**
Open *Settings*, choose the service, paste the key and tap *Test connection &
save*. Each screen explains where to create the key with the least access.

**Can I try the app without any keys?**
Yes. Tap *Try with sample data* on the first screen.

**GoDaddy says "access denied".**
GoDaddy only gives API access to eligible accounts. You don't need it: enter
your domain under *Settings → Domain* and the app reads the expiry date and
common DNS records from public sources.

**The domain card can't find my expiry date.**
Some country domains (for example `.tr`) don't publish registration data. DNS
records and the SSL check still work.

**How do I remove my data?**
*Settings → Remove all keys and reset*, or delete the app. Nothing is stored
anywhere else.

---

Infra Pulse is an independent app and is not affiliated with or endorsed by
Vercel, Render, GoDaddy or UptimeRobot.
