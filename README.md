# Oranj Website

Static holding site for `oranj.com.au`, including:
- Home page
- Privacy Policy
- Facebook Data Deletion Instructions

## Cloudflare Pages Deployment

This project is a **Cloudflare Pages** static site.

- Build command: *(leave empty)* or `npm run deploy:pages` for manual Wrangler deployments
- Build output directory: `.`

If using a deploy command, use:

```bash
npx wrangler pages deploy . --project-name=oranj
```

Do **not** use `wrangler deploy` (that is a Workers command).
