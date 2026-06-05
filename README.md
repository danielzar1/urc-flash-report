# URC Flash Report

Universal Recycling Company — monthly **Flash** investor report (single-month, year-on-year).

This repository hosts a single self-contained, **AES‑256‑GCM encrypted** HTML page
(`index.html`) served via GitHub Pages. The page is **passphrase-gated** — the figures
are not visible without the passphrase, which is shared separately with authorised
recipients only.

**Live page:** https://danielzar1.github.io/urc-flash-report/

## Notes
- The deliverable is the encrypted `index.html` only. No source data, spreadsheets,
  extracted JSON, build scripts, or passphrases are ever committed to this repo.
- To publish a new month, regenerate the gated report from the source project and
  replace `index.html`, then commit and push.
