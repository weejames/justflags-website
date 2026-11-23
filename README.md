# Just Flags website

Static marketing site for [Just Flags](https://github.com/weejames/justflags), the app for iPhone and iPad for learning the flags of the world. Plain HTML and CSS, no build step.

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

- `assets/screenshots/` — 1600×1200 iPad and 600px-wide `iphone-*` JPEGs made from the simulator captures in the app repo's `design/app-store/screenshots/`
- `assets/icon-256.png`, `favicon.png`, `apple-touch-icon.png` — resized from the app's 1024px icon
- `assets/fonts/` — Fredoka and Nunito, the app's fonts, under the SIL Open Font License

## App Store

The app is live at <https://apps.apple.com/app/id6826595814>. Every page has a Smart App Banner (`apple-itunes-app` meta tag) for Safari on iOS, and the home page's `#app-store` button links to the listing. To use Apple's official badge artwork instead, get it from <https://developer.apple.com/app-store/marketing/guidelines/>, save it under `assets/`, and put it inside that link.
