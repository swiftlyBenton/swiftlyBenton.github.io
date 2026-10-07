# Benton Struchtemeyer — Portfolio

Static portfolio site for **bentonstruchtemeyer.com**, aimed at aerospace internship recruiters.

## Stack

- Plain HTML, CSS, and a small `script.js` for mobile navigation
- No build step, frameworks, or package manager
- Hosted on **GitHub Pages** with a custom domain

## Contents

| File | Purpose |
|------|---------|
| `index.html` | Single-page portfolio |
| `styles.css` | Layout and theme |
| `script.js` | Mobile nav toggle + footer year |
| `CNAME` | Custom domain: `bentonstruchtemeyer.com` |
| `favicon.svg` | Site icon |

## Local preview

Open `index.html` in a browser, or from this folder:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## GitHub Pages + custom domain

1. Push this folder to a GitHub repository (e.g. a user/org Pages repo or a `/docs` / `gh-pages` setup).
2. In the repo **Settings → Pages**, enable GitHub Pages from the branch that contains these files.
3. Confirm the `CNAME` file is present (it should read exactly `bentonstruchtemeyer.com`).
4. At your domain registrar (Squarespace Domains), point DNS at GitHub Pages per [GitHub’s custom domain docs](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).
5. In Pages settings, enable **Enforce HTTPS** once the certificate is ready.

## Editing tips

- Update the email placeholder in the Contact section of `index.html` (search for `Add your email`).
- Add new experience or project cards by copying an existing card block.
- Keep claims accurate — recruiters notice invented details.

## Owner

Benton Struchtemeyer · [LinkedIn](https://linkedin.com/in/bentons) · [GitHub](https://github.com/swiftlyBenton)
