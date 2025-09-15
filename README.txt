CHECK VERO — BRAND PACK (Vercel proxy ready)

What is this?
- /public holds static files that Vercel serves at https://www.checkvero.org/<filename>.
- /styles/tokens.css has color & type tokens (for when you build your own site).
- vercel.json keeps your proxy rewrite to the Caffeine site.
- email_signature.html is a copy-paste email signature.

How to use (short):
1) Copy /public, /styles and vercel.json into your GitHub repo (checkvero-proxy) and push.
2) Vercel deploys automatically.
3) Test: https://www.checkvero.org/favicon.svg and /og-image.svg

Notes:
- The proxy won't change the head tags of the Caffeine page. These assets are still useful for social, docs and email.
- When you later own your site HTML, add <link rel="icon" ...> and Open Graph <meta> tags to use these assets.
