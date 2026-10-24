# Just Flags website

Static marketing site for [Just Flags](https://github.com/weejames/justflags), the iPad app for learning the flags of the world. Plain HTML and CSS, no build step.

| Page | Path | App Store Connect field |
|---|---|---|
| Home | `index.html` | Marketing URL |
| Support | `support.html` | Support URL |
| Privacy policy | `privacy.html` | Privacy Policy URL |

## Preview locally

```bash
uv run --no-project python -m http.server 8417
```

Then open <http://localhost:8417>.

## Assets

- `assets/screenshots/` — 1600×1200 JPEGs made from the simulator captures in the app repo's `design/app-store/screenshots/`
- `assets/icon-256.png`, `favicon.png`, `apple-touch-icon.png` — resized from the app's 1024px icon
- `assets/fonts/` — Fredoka and Nunito, the app's fonts, under the SIL Open Font License

## When the app goes live

Replace the "Coming soon" block (`#app-store` in `index.html`) with Apple's official "Download on the App Store" badge from <https://developer.apple.com/app-store/marketing/guidelines/>, linked to the app's App Store URL.
