# My Gaming Dad

A responsive, static gaming landing page for **My Gaming Dad**. Built with HTML, CSS, JavaScript, and custom SVG artwork. No build tools, frameworks, or paid hosting required.

## What's included

- `index.html` — homepage content and search/social metadata
- `styles.css` — layout, neon theme, animations, and mobile styling
- `script.js` — responsive menu, working game filters, reveal effects, and automatic footer year
- `assets/hero-controller.svg` — original neon controller illustration
- `assets/game-west.svg` — Western adventure art
- `assets/game-hoops.svg` — basketball art
- `assets/game-siege.svg` — tactical gaming art
- `assets/favicon.svg` — browser icon
- `assets/gaming-dad-avatar.jpg` — profile art from your earlier GitHub avatar
- `assets/social-preview.png` — preview for sharing your site on social media

## Preview on your Windows PC

1. Unzip the folder.
2. Open `index.html` in Chrome, Edge, or Firefox.
3. Click the menu, game filters, and links to explore.

## Publish with GitHub Pages

1. Create or open your existing GitHub repository **mygamerpcwebsite**.
2. Upload the **contents** of this folder to the repository's root (ensure `index.html` is in the root, not in a second nested folder).
3. Open the repository **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose your default branch (often `main`) and folder `/ (root)`, then **Save**.
6. When GitHub Pages finishes publishing, GitHub will show the website URL in Pages settings.

Documentation: https://docs.github.com/en/pages/quickstart

If your repository is a project site (e.g. `mygamerpcwebsite`), GitHub Pages normally publishes it at `https://YOUR-USERNAME.github.io/mygamerpcwebsite/`.

## Make it yours

- Update the headings and About section in `index.html`.
- Replace game descriptions and illustrations with your own footage and screenshots (only if you have the rights to publish them).
- Add your actual Twitch, YouTube, or Discord URLs when you have them. The current page does not invent these links or pretend that videos have been uploaded.
- Adjust colors in the `:root` block at the top of `styles.css`.
- The current avatar is *illustrative artwork*, not a verified portrait.
- Social sharing previews using the relative `og:image` may need to be changed to the **absolute public URL** of your uploaded `assets/social-preview.png` after deployment.
- Google Fonts load from Google's CDN when connected to the internet. The page has local fallback fonts and works offline, but typography may vary.

## Privacy, accessibility and safety

- No contact form, analytics, trackers, cookies, external JavaScript, or backend.
- Fonts are the only external resource (Google Fonts). Remove the top `@import` in `styles.css` if you want a fully offline page with no third-party requests.
- Supports mobile, keyboard navigation, and reduced motion preferences.
- Graphics are original vector illustrations made for this site. Commercial game names are descriptive references, not official affiliations.

## Site status

This is a **polished landing-page starter**. It is not yet a video hosting platform, member portal, store, or CMS. Game category filters, section links, and the mobile menu are functional. More social/community functionality can be added when real account URLs and content are available.
