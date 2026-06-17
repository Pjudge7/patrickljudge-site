# Patrick L. Judge personal website - custom domain ready

Primary domain: https://patrickljudge.com/
Redirect/short domain: https://pljca.com/ -> https://patrickljudge.com/

Upload these files to the root of the GitHub repository: index.html, robots.txt, sitemap.xml, README.md, CNAME.

GitHub Pages settings: Deploy from a branch -> main -> / root. Custom domain: patrickljudge.com. Enforce HTTPS once available.

Cloudflare DNS for patrickljudge.com:
- A @ 185.199.108.153 DNS only
- A @ 185.199.109.153 DNS only
- A @ 185.199.110.153 DNS only
- A @ 185.199.111.153 DNS only
- CNAME www pjudge7.github.io DNS only

Cloudflare redirect for pljca.com:
- Add proxied DNS records for @ and www (for redirect handling).
- Create a Redirect Rule to 301 redirect pljca.com and www.pljca.com to https://patrickljudge.com/ while preserving path/query.

Professional email:
- Set up Cloudflare Email Routing or Zoho Mail for advisory@patrickljudge.com and patrick@patrickljudge.com.
- FormSubmit action currently uses advisory@patrickljudge.com. Submit one test form after email routing is active to confirm FormSubmit forwarding.
