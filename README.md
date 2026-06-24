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

- Phone number
- Booking link or email
- Service area
- Pricing/menu details
- Social profile links, if desired

## DNS

The root domain should point to Render with:

- `A` record: host `@`, value `216.24.57.1`

For `www`, add:

- `CNAME` record: host `www`, value `groomingbymahlorie.onrender.com`
