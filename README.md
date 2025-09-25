# Scam Patterns — Case Study (Responsible Disclosure)

**TL;DR:** Analysis of a scam website pattern observed on a public GitHub Pages site. The repo documents indicators of compromise, common social-engineering tactics, and safe guidance for researchers and victims. All user data has been redacted; no private data is published here.

## What this repo contains
- `artifacts/` — Screenshots of public-facing pages (no PII).  
- `indicators.txt` — Hostnames, repo links, and observable endpoints (public info only).  
- `analysis.md` — Notes on attack flow, UI tricks, and red flags (for defenders).  
- `reproduce-in-lab.md` — Step-by-step instructions to recreate the vulnerable setup **locally** for learning (use VMs; do not deploy publicly).  
- `responsible_disclosure.md` — A template & checklist for reporting scams to platforms/CSIRTs/ISPs.

## Responsible disclosure
This repo is intentionally NOT publishing any user data or database dumps. If you possess sensitive data from an incident, do NOT upload it here — contact your national CERT or platform abuse team and follow secure evidence transfer protocols.

## Contact / Creds
Maintainer: `404saint` — volunteer researcher focused on fraud patterns and defensive tooling.  
If you have tips or would like to collaborate on tooling for takedown/reporting, open an issue (no PII).

## License
MIT — educational and defensive use only.
