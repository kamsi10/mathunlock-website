# MathUnlock Website

This repository contains the Privacy Policy and Terms of Service pages for the MathUnlock iOS app.

## Files

- `privacy-policy.html` - Privacy Policy page
- `terms-of-service.html` - Terms of Service page

## Setup with GitHub Pages

1. Push these files to your GitHub repository
2. Go to Settings → Pages in your GitHub repo
3. Under "Source", select "Deploy from a branch"
4. Choose `main` (or `master`) branch and `/ (root)` folder
5. Click Save

Your pages will be available at:
- `https://yourusername.github.io/mathunlock-website/privacy-policy.html`
- `https://yourusername.github.io/mathunlock-website/terms-of-service.html`

## Custom Domain Setup

If you have a custom domain:

1. Create a `CNAME` file in this directory with your domain name (e.g., `mathunlock.app`)
2. In your domain's DNS settings, add:
   - **A records** pointing to GitHub Pages IPs:
     - `185.199.108.153`
     - `185.199.109.153`
     - `185.199.110.153`
     - `185.199.111.153`
   - Or a **CNAME** record: `@` → `yourusername.github.io`
3. In GitHub Pages settings, add your custom domain

Your pages will then be available at:
- `https://yourdomain.com/privacy-policy.html`
- `https://yourdomain.com/terms-of-service.html`

## Updating Content

Simply edit the HTML files and push changes to GitHub. GitHub Pages will automatically update within a few minutes.
