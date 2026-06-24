# Grooming by Mahlorie

Static website draft for `groomingbymahlorie.com`.

## Live URLs

- Render: https://groomingbymahlorie.onrender.com/
- Primary domain: https://groomingbymahlorie.com/

## Local Preview

Open `index.html` directly in a browser, or run:

```powershell
npx serve .
```

## Render Static Site Settings

- Type: Static Site
- Build command: `true`
- Publish directory: `.`
- Custom domain: `groomingbymahlorie.com`

## Launch Checklist

Replace these placeholders before launch:

- Pricing/menu details
- Social profile links, if desired

## Photos

Put optimized, website-ready images in:

- `assets/photos/hero/` for future hero image options.
- `assets/photos/grooms/` for the completed grooms gallery.

Keep full-resolution originals outside the repo, then export edited web copies into these folders.

## Contact Form

This is a static Render site, so a real form needs a form backend. Good options:

- Formspree: easiest for a small static site; create a form endpoint, then set the HTML form `action` to that endpoint.
- A small Render web service: more control, but more code and maintenance.

For now, the site uses call/text and email links.

## Email Forwarding

Namecheap can forward `hello@groomingbymahlorie.com` to `mahlorie.vahldick@icloud.com` if the domain uses Namecheap DNS. This creates a receiving alias only; it does not let Mahlorie send outbound mail as `hello@groomingbymahlorie.com`.

## DNS

The root domain should point to Render with:

- `A` record: host `@`, value `216.24.57.1`

For `www`, add:

- `CNAME` record: host `www`, value `groomingbymahlorie.onrender.com`
