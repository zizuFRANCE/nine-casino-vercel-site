Nine Casino Vercel static site

Files:
- index.html — main page
- style.css — design
- robots.txt — crawling rules
- sitemap.xml — sitemap
- vercel.json — Vercel static settings

How to deploy on Vercel:
1. Go to https://vercel.com/
2. Click Add New → Project
3. Import this folder from GitHub or use Vercel CLI
4. Framework Preset: Other
5. Build Command: leave empty
6. Output Directory: leave empty
7. Deploy

How to change the domain:
Replace this URL in index.html, robots.txt and sitemap.xml:
https://nine-casino-vercel.vercel.app/

With your real domain, for example:
https://your-domain.com/

Important SEO places in index.html:
- <link rel="canonical">
- <meta property="og:url">
- all sitemap and robots references
