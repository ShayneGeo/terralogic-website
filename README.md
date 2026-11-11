# TerraLogic Systems LLC website

A static, GitHub Pages-ready website for `terralogicsystems.com`.

## Publish with GitHub Pages

1. Create a GitHub repository.
2. Upload the contents of this folder to the repository root.
3. In GitHub, open **Settings → Pages**.
4. Select **Deploy from a branch**.
5. Choose `main` and `/ (root)`.
6. Save.
7. Configure the DNS records GitHub provides for `terralogicsystems.com`.
8. Enable **Enforce HTTPS** in GitHub Pages once the domain is verified.

The included `CNAME` file already contains `terralogicsystems.com`.

## Enable Pay Invoice

The payment button is intentionally disabled until you add a Stripe Payment Link. In `script.js`, replace:

`const PAYMENT_URL="";`

with a PUBLIC Stripe-hosted payment URL such as:

`const PAYMENT_URL="https://buy.stripe.com/your_public_link";`

Never put a Stripe secret key, bank information, API token, password, or any other credential in this repository.

## Security

This is a static site. It contains no backend, database, login system, payment-card fields, analytics trackers, or third-party JavaScript. A restrictive Content Security Policy is included. Payments should be handed off to Stripe's HTTPS-hosted checkout. The site intentionally does not publish a residential street address.

## Contact email

The site currently uses `magstadt.shayne@hotmail.com`. Replace it in `index.html` when you create a TerraLogic-domain business email.

## Generated illustration note

The natural-history imagery was generated specifically for this TerraLogic website concept, inspired by nineteenth-century scientific plates and natural-history engraving traditions. Optimized crops are in `assets/`; the full generated source images are preserved under `assets/source-art/`.
