# Golden Talent — website

Self-contained, bilingual (AR/EN) marketing site for the academy. Single
`index.html` with inlined CSS/JS, the brand's Tajawal font, and real photos +
member-app screenshots. Dark-teal identity matching the app.

## Preview
Open `index.html` in a browser, or serve statically:
```
npx serve apps/web          # or: python3 -m http.server -d apps/web
```

## Deploy (Vercel)
Static — no build step. Point a Vercel project at `apps/web` (or drag-drop the
folder). The AR/EN toggle is client-side (no i18n routing); the language is
remembered in localStorage. Legal pages live in `legal/`.

## Assets
`assets/photos` (pitch/stadium), `assets/app` (app screenshots), `assets/fonts`
(Tajawal), `assets/crest.png`. Store badges show "قريباً / Soon" until the app is
published — swap the `<a>` href in the two `.store` blocks with the real store URLs.
