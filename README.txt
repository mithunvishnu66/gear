Gear 5 Studios website (gear5studios.com)

This is a static site: upload the whole folder as it is to any web host
(Netlify, Vercel, Cloudflare Pages, Hostinger, cPanel public_html...).
No build step, no server code. index.html must sit at the site root.

Contents
- index.html      the whole site
- reels/          client reels (.mp4) and their cover images (.jpg)
- lab/            AI lab stills
- og.jpg          share preview image (1200x630)
- robots.txt, sitemap.xml   for Google

Notes for the host
- Point gear5studios.com (and www) here, with HTTPS on.
- Videos stream best when the host serves .mp4 with byte-range support (all the hosts above do).
- Libraries load from cdnjs / jsdelivr and fonts from Google Fonts, so no extra files are needed.
- After going live, submit https://gear5studios.com/sitemap.xml in Google Search Console.
