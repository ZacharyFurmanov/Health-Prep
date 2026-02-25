# PrepSocial Static Site

Static multi-page website for PrepSocial, ready for Cloudflare Pages.

## Files

- `index.html` - landing page
- `sessions.html` - session listings and sign-up CTA
- `about.html` - how it works
- `faq.html` - common questions
- `styles.css` - shared site styles
- `script.js` - responsive menu and reveal animations
- `_redirects` - clean route support on Cloudflare Pages
- `_headers` - basic security headers

## Deploy to Cloudflare Pages

1. Push this project to a Git repository.
2. In Cloudflare Dashboard, go to Pages and create a new project from that repo.
3. Use these settings:
   - Framework preset: `None`
   - Build command: leave empty
   - Build output directory: `/`
4. Deploy.

## Local preview

You can preview locally with any static server, for example:

```bash
npx serve .
```
