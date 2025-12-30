# AI Visual Search RFP — Proposal Website

This repo contains a **static, single-page proposal / RFP website** to solicit vendors for an **AI-based visual similarity search** solution for a **B2B gold & diamond jewelry manufacturer** with a large 2D + 3D CAD design library (~300,000 SKUs).

## What’s included

- **RFP landing page**: requirements, integrations, deliverables, and a clear call-to-action.
- **Vendor response builder**: a small form that generates a **copyable email template** (no backend; runs locally in the browser).

## Customize before sharing

Edit `index.html` and update the contact block in the “Respond as a vendor” section:

- `Contact: Your Name`
- `Email: your.name@yourcompany.com`
- `Phone: +1 (555) 010-0200`

You can also adjust:

- Scope/requirements language
- Evaluation expectations (pilot vs production)
- Any security/deployment constraints

## Publish

This is a static site, so you can host it anywhere:

- **GitHub Pages** (recommended): enable Pages for the repo and serve from the branch/root.
- Any static host (S3/CloudFront, Netlify, Vercel static, etc.).