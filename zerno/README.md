# Zerno — coffee roaster & café, Kazan

A single-page site with all fonts, images and scripts bundled into `index.html`. It has no build step and no dependencies.

## Language

The site opens in **English** by default. Russian is still built in.

| How | English | Russian |
|---|---|---|
| Design tweak (Tweaks panel → *Language*) | `English` (default) | `Русский` |
| URL parameter (overrides the tweak) | `?lang=en` | `?lang=ru` |

Both languages use the same fonts (Cormorant Garamond for headings, Manrope for body text) and the same layout. Only the text changes. The page also sets `<html lang>` and the browser tab title to match.

## Deploy (Vercel)

The repo is connected to the Vercel project `zerno`; every push to `main` deploys to production. The root `vercel.json` serves `zerno/index.html` at `/`, so no Root Directory or build settings are needed.
