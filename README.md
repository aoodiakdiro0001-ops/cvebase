# 🗄️ CVEbase — Vulnerability Archive & Tracker (MIT)

Searchable CVE archive with affected-library lookup and stack-based
alerts. UI in EN/TR/AR. Static single file + README.

## Data (all public)

- **Archive:** pull by CVE-ID / vendor+product / recent-30 from
  `cve.circl.lu/api` into a **persistent local archive** (dedupe, 2000 cap,
  offline search + severity/year filters, export/import JSON).
- **Libraries:** OSV `api.osv.dev/v1/query` by ecosystem+package —
  real recorded vulns; findings auto-merge into the archive.
- **Detail modal:** CVSS, CWE, affected configs, references + NVD/Exploit-DB links.
- **Upstream count:** CIRCL `/api/dbInfo` hero stat.

## Alerts (SaaS)

- **Free (works now):** named tech stacks (keywords) + browser Notification
  API + 5-min auto-pull while open.
- **Pro $5/mo (needs backend):** Telegram instant + Discord webhooks +
  priority API. Interest saved locally; payment box (BTC/USDT-TRC20/IBANs)
  included. Wire a worker before charging.

## Money

- `CONFIG.ads` (AdSense/Carbon) security & cloud slots.
- Pro $5/mo payment box with copy buttons.

## Contact

📧 baranavisat@gmail.com · 📞 +90 531 326 37 22 · WhatsApp

## Run

```bash
cd cvebase
python3 -m http.server 8080
```

## License

MIT.
