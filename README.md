# Edmore Taroiwa — 3D Portfolio

A responsive, dark futuristic portfolio with subtle 3D styling, hover tilt, animated reveal effects, project cards, about section, skills, contact form, and SEO starter files.

## What's included

- `index.html` — portfolio and metadata / structured data
- `styles.css` — responsive design and visual effects
- `script.js` — mobile navigation, motion effects, tilt, email-based contact form
- `sitemap.xml` and `robots.txt`
- `site.webmanifest`, `favicon.svg`, `404.html`
- `assets/` — supplied portrait photos

## Before publishing — important

1. **Set your real contact email.** Replace `REPLACE_WITH_YOUR_EMAIL@example.com` in both `index.html` and `script.js`.
2. **Set the final website URL.** Search the project for `https://edmoretaroiwa.github.io/portfolio/` and replace it with your actual canonical URL in `index.html`, `robots.txt`, `sitemap.xml`, and the JSON-LD metadata.
3. **Verify project details and links.** The portfolio includes Afri Genius, EduVille Learning Africa, and ZimBeats based on the available project context. Replace placeholder GitHub links with each exact repository or live demo when ready. Remove or edit any claim that is not accurate.
4. **Do not put private information on the public site.** Add only contact details and project information you are happy to share publicly.

## Publish with GitHub Pages

1. Create a GitHub repository named `portfolio` under `edmoretaroiwa`.
2. Upload the contents of this folder to the repository root (not the outer ZIP folder).
3. In GitHub, open **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Once GitHub Pages gives you the public URL, update the canonical URL in all SEO files to match it.
5. Add the sitemap URL to Google Search Console and Bing Webmaster Tools after the site is publicly accessible.

If you instead use a custom domain, configure it in GitHub Pages, add the required DNS records with your domain provider, enable HTTPS, and update every canonical/sitemap URL to the custom domain.

## SEO notes

The site includes crawl directives, a sitemap, canonical URL, descriptive title and description, Open Graph tags, a social sharing image, Person structured data, a favicon and a manifest. These help crawlers understand the site but **cannot guarantee indexing or ranking**. Search engines need the site to be live and publicly accessible, and you should submit the sitemap in their webmaster tools.

The included contact form opens the visitor's email app; it does not store submissions or send them to a database. To collect messages directly on the site, connect a backend/form service (for example, a secure serverless function or form provider) and add spam protection. Never expose database service-role keys in frontend code.
