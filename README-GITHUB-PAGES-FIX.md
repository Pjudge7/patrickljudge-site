# GitHub Pages Deployment Fix

Upload these files directly to the root of the GitHub repository:

- index.html
- .nojekyll
- robots.txt
- sitemap.xml
- CNAME

The .nojekyll file is intentionally blank. It tells GitHub Pages not to process the site with Jekyll.

After uploading:
1. Commit directly to main.
2. Go to Actions.
3. Confirm the pages-build-deployment workflow turns green.
4. Open http://patrickljudge.com/ in an incognito window.
