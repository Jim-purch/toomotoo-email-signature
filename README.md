# TOOMOTOO Email Signature Generator

A dynamic, browser-based email signature generator for **TOOMOTOO (Tianjin) International Trading Co., Ltd** — a one-stop forklift parts supplier.

## Features

- **Live Editor** — Edit all signature fields (name, title, phone, email, website, address, company info) and see changes in real time.
- **Avatar Upload** — Upload a personal photo that appears in the bottom-left of the signature. Circular crop with adjustable size (48–120px).
- **Logo Support** — Ships with the embedded TOOMOTOO logo by default; upload a custom logo anytime.
- **Color Customization** — Adjust accent and navy colors to match your brand.
- **Two Signature Versions**
  - **Version A** — Logo + avatar + full contact details (recommended for Gmail, Outlook, etc.)
  - **Version B** — Pure text version for maximum compatibility across strict email clients.
- **One-Click Copy** — Copy the rich-text signature directly to your clipboard and paste into any email client's signature settings.
- **Export HTML** — Download a standalone HTML file of the current signature.
- **Auto-Save** — All edits are saved to `localStorage`; your settings persist across sessions.

## Live Demo

Visit the published site via GitHub Pages:

> https://jim-purch.github.io/toomotoo-email-signature/

## Usage

1. Open the [live demo](https://jim-purch.github.io/toomotoo-email-signature/) or `index.html` locally.
2. Fill in your details in the left editor panel and upload your avatar/logo.
3. Click **"复制签名" (Copy Signature)**.
4. Paste into your email client's signature settings (Gmail, Outlook, QQ Mail, Apple Mail, etc.).

## Tech Stack

- **Vanilla HTML / CSS / JavaScript** — no build step, no dependencies.
- **Self-contained** — the TOOMOTOO logo is embedded as base64; works fully offline.
- **Email-client-compatible** — signatures use table layouts + inline styles for maximum rendering compatibility.

## Project Structure

```
├── index.html              # The full signature generator app
├── assets/
│   └── toomotoo-logo.png   # Standalone logo file (also embedded in index.html)
└── README.md
```

## License

© TOOMOTOO (Tianjin) International Trading Co., Ltd. All rights reserved.

---

**TOOMOTOO** — One-Stop Forklift Parts Supplier · https://toomotoo.com
