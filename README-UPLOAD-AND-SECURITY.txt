PLJ Digital Business Card - Upload & Security Notes

Recommended URL:
https://www.patrickljudge.com/card/

Upload the contents of this folder into a /card/ directory on your website host.
Do not upload the parent folder itself unless your host expects it.

Files included:
- index.html: mobile-friendly digital card page
- patrick-l-judge.vcf: downloadable contact file
- assets/patrick-l-judge-business-card.png: visual card with embedded scannable vCard QR code
- assets/vcard-qr-code.png: standalone vCard QR code
- .htaccess: Apache security headers, HTTPS redirect, and directory listing protection
- _headers: Netlify/Cloudflare Pages-style security headers
- robots.txt: basic crawler rule

Security checklist after upload:
1. Confirm the live page opens with https://, not http://.
2. Enable "force HTTPS" or "SSL always on" in your hosting dashboard.
3. Confirm there is no directory listing at /card/assets/.
4. Keep the page static. It uses no JavaScript, no tracking scripts, no forms, and no third-party dependencies.
5. Keep the vCard QR and Save Contact button pointing to the same contact details.

Note: Security headers only work if your host supports .htaccess or _headers. If your host uses Wix, Squarespace, GoDaddy Website Builder, or another managed builder, use that platform's SSL/security settings instead.
