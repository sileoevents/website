# sileoevents.com

Static site for Sileo Events. No build step: Vercel serves these files as they are.

- `index.html` : the whole site (copy, styles and the Three.js scroll world)
- `og.png` : the share image (1200 x 630) that iMessage, WhatsApp, LinkedIn, Facebook, X and Slack show when the link is sent
- `favicon.svg` : browser tab icon
- `apple-touch-icon.png` : icon when the site is saved to an iPhone home screen
- `logo.png` : square logo that Google can show in search
- `brand/` : the Quiet Frame mark (colour and single colour SVG)
- `robots.txt`, `sitemap.xml` : search engines
- `vercel.json` : headers and clean URLs

Edit copy directly in `index.html`, commit, and Vercel redeploys automatically.

Note: link previews are cached by each app. After changing `og.png`, new shares pick it up, but a link already sent keeps its old preview.
