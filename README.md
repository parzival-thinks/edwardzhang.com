# edwardzhang.com

Static site served by GitHub Pages at https://www.edwardzhang.com. Plain HTML and CSS, no build step: edit a page and push.

- Pages live at the repo root (`about.html` is served at `/about`).
- `home.html` redirects to `/`, because the old Squarespace site also answered at `/home`.
- `CNAME` sets the custom domain. Keep it.

Preview locally:

```bash
npx serve .
```

## DNS (GoDaddy)

Only the website records point at GitHub. Leave MX and TXT records alone.

| Type  | Name | Value |
|-------|------|-------|
| A     | @    | 185.199.108.153 |
| A     | @    | 185.199.109.153 |
| A     | @    | 185.199.110.153 |
| A     | @    | 185.199.111.153 |
| CNAME | www  | parzival-thinks.github.io |
