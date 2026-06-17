# quickprotect-support

Marketing, support, and privacy site for **QuickProtect** — served via GitHub Pages at
[quickprotect.app](https://quickprotect.app).

## Structure

| Path | Purpose |
|---|---|
| `index.html` | Landing page — overview, screenshots, changelog, compatibility |
| `support/index.html` | Support page (App Store "Support URL") — contact + FAQ |
| `support/privacy.html` | Privacy policy (App Store "Privacy Policy URL") |
| `privacy.html` | Redirect to `support/privacy.html` |
| `assets/icon.png` | App icon (1024², from `QuickProtect.icns`) |
| `assets/shots/` | App Store screenshots |
| `CNAME` | Custom domain: `quickprotect.app` |
| `.nojekyll` | Serve files as-is (no Jekyll processing) |

## Deploy

1. Create a public GitHub repo `cb2206/quickprotect-support` and push this directory.
2. Repo **Settings → Pages** → Source: `main`, folder `/ (root)`.
3. Add DNS for `quickprotect.app` once the domain is registered:
   - Apex `A`/`ALIAS` records to GitHub Pages IPs, or
   - `CNAME` for `www` → `cb2206.github.io`.
4. Until DNS resolves, the site is reachable at `https://cb2206.github.io/quickprotect-support/`.

## App Store Connect URLs

- **Support URL:** `https://quickprotect.app/support/`
- **Privacy Policy URL:** `https://quickprotect.app/support/privacy.html`
- **Marketing URL:** `https://quickprotect.app/`

(Use the `cb2206.github.io` equivalents until the custom domain is live.)
