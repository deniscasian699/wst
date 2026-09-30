<div align="center">

# 🔐 Security Policy — WST WiFi Speed Test

</div>

---

## Supported Versions

| Version | Supported |
|---|:---:|
| Latest (Google Play) | ✅ Active |
| Previous versions | ❌ No support |

Always use the latest version of WST WiFi Speed Test available on Google Play to
ensure you have the most recent security fixes and improvements.

---

## Reporting a Vulnerability

If you discover a security vulnerability in WST WiFi Speed Test, please report it
**responsibly** and **privately:**

> ⚠️ **Do not open a public GitHub issue for security vulnerabilities.**
> This could expose users before a fix is available.

### How to Report

1. Send an email to **[support@rdcapps.com](mailto:support@rdcapps.com)**
   with the subject line: `[SECURITY] WST WiFi Speed Test Vulnerability Report`
2. Include in your report:
   - A clear description of the vulnerability
   - Steps to reproduce the issue
   - Potential impact assessment
   - Your suggested fix (if any)
   - Your Android version and WST WiFi Speed Test version

### Response Timeline

These are response targets, not guaranteed service levels.

| Step | Timeline |
|---|---|
| Acknowledgement | Target: within 72 hours |
| Assessment | Target: within 7 days |
| Fix release | Depends on severity |

We appreciate responsible disclosure and will credit researchers who help
keep WST WiFi Speed Test secure (with their permission).

---

## Scope

| In Scope ✅ | Out of Scope ❌ |
|---|---|
| WST WiFi Speed Test Android app | Public diagnostic endpoint infrastructure |
| In-app purchase and consent flows | Google advertising infrastructure |
| Local history and CSV export handling | Google Play / RevenueCat infrastructure |
| App-owned network and UI handling | Physical device attacks |

---

## Known Security Practices

- Primary HTTP test endpoints use **HTTPS**; manually selectable legacy endpoints may use **HTTP**. ICMP probes are not HTTPS.
- Google AdMob / UMP advertising requests are gated by consent status and valid ad-removal entitlements.
- ✅ All preferences stored locally using Android SharedPreferences
- ✅ Purchase verification handled by RevenueCat (server-side)

---

*Thank you for helping keep WST WiFi Speed Test and its users safe. 📶*
