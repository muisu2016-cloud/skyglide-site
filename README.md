# Sky Glide — App Store support site (local, not pushed)

English-only static site for App Store Connect URLs. **Nothing was pushed to a remote.**

## Files

| File | Use in App Store Connect |
|------|--------------------------|
| `index.html` | Support URL / Marketing URL |
| `privacy.html` | Privacy Policy URL |
| `terms.html` | Terms (linked from the site) |
| `style.css` | Styles |

## Before publish

1. Support email is set to `muisu2016@icloud.com`.
2. Preview locally: open `index.html` in a browser.
3. When you have a GitHub account: create a public repo (e.g. `skyglide-site`), upload this folder to `main`, enable Pages from `/` (root).
4. In App Store Connect:
   - Privacy Policy URL → `https://<user>.github.io/skyglide-site/privacy.html`
   - Support URL → `https://<user>.github.io/skyglide-site/`

## Publisher

- App: **Sky Glide**
- Company: **MAX SPACE CONSTRUCTION LTD**
- Bundle ID: `com.maxspace.soaring`
- Language: **English only**
- Effective date: **16 October 2026**
