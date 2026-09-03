# periplous-site

The public pages for **Periplous**, served by GitHub Pages from `docs/` at
<https://stavrop.github.io/periplous/>.

Four pages, no build step:

| Page | Why it exists |
|---|---|
| `index.html` | What the app is. The App Store marketing URL. |
| `privacy.html` | Required by App Store Connect, and the app's whole argument. |
| `support.html` | Required by App Store Connect. Real answers, not a form. |
| `terms.html` | Required for a subscription (3.1.2) — the standard Apple EULA plus what Pro costs. **The App Store description must link to this and to the privacy policy**; Deltion was rejected once for leaving it out. |

`style.css` uses the app's own chrome tokens from `Periplous/DesignSystem`. It
is almost colourless on purpose: Sediment takes its colour from the user's
photographs, and a website has none to take, so the only colour on the page is
the strata band standing in for them.
