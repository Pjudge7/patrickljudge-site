# Patrick L. Judge Website - Custom Domain Fix

This package fixes the site launch issue by replacing the broken plain-text `index.html` with a valid, self-contained HTML website.

## Files to upload to repo root

Upload these files to the root of `Pjudge7/patrickljudge-site`:

- `index.html`
- `robots.txt`
- `sitemap.xml`
- `CNAME`
- `README.md`

## GitHub Pages settings

Use:

- Source: Deploy from a branch
- Branch: main
- Folder: / root
- Custom domain: patrickljudge.com

## Cloudflare DNS for patrickljudge.com

Set GitHub Pages records:

A @ 185.199.108.153 DNS only
A @ 185.199.109.153 DNS only
A @ 185.199.110.153 DNS only
A @ 185.199.111.153 DNS only
CNAME www pjudge7.github.io DNS only

Cloudflare SSL/TLS mode should usually be Full. If GitHub HTTPS verification is not ready, wait and re-check later.

## After upload

Test:

https://patrickljudge.com/?refresh=1
https://www.patrickljudge.com/?refresh=1
https://pjudge7.github.io/patrickljudge-site/?refresh=1
