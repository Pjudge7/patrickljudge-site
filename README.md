# Patrick L. Judge Personal Website

A professional Vite + React + TypeScript website for Patrick L. Judge, Chief AI Strategy & Digital Transformation Executive.

## Local setup

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
npm run preview
```

## Publish with GitHub Pages

1. Create a public GitHub repository named `patrickljudge-site`.
2. Upload/push these files to the `main` branch.
3. Go to **Settings -> Pages**.
4. Under **Build and deployment**, choose **GitHub Actions**.
5. The included `.github/workflows/deploy.yml` workflow will build and deploy the site.
6. If you are using the GitHub project URL `https://USERNAME.github.io/patrickljudge-site/`, add an Actions variable named `VITE_BASE_PATH` with value `/patrickljudge-site/`. If using a custom domain, leave it unset.

## Publish with Netlify

1. Create a Netlify account.
2. Add new site -> Import from GitHub.
3. Select this repository.
4. Build command: `npm run build`.
5. Publish directory: `dist`.
6. Deploy.

## Contact form

The site currently uses direct email and phone links for reliable contact. To add a live web form, connect Formspree, Netlify Forms, or a CRM endpoint.

## SEO launch checklist

- Add final custom domain in `index.html`, `robots.txt`, and `sitemap.xml`.
- Add the live URL to LinkedIn.
- Submit the sitemap in Google Search Console.
- Publish 3-5 thought leadership posts.
