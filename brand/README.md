# brand/

Static Granid **brand artifacts** with stable, hotlinkable URLs.
Generated — do not edit here. Source (private): `stefanoleone/granid-designsystem`
(`assets/` + `npm run export:social`; ADR 0005, 2026-07-17 amendment).

| File | What | Use |
| --- | --- | --- |
| `granid-wordmark-black.png` | Black "Granid" wordmark (with the red dot), transparent background, 555×145 | Email signatures, light backgrounds |

## Email signatures

Mail clients (Outlook especially) don't reliably render SVG, so use this PNG.
Reference the **raw URL on `main`** — it is stable and does not change on a
design-system version bump, so you set the signature once:

```
https://raw.githubusercontent.com/stefanoleone/granid-ds-dist/main/brand/granid-wordmark-black.png
```

```html
<img
  src="https://raw.githubusercontent.com/stefanoleone/granid-ds-dist/main/brand/granid-wordmark-black.png"
  alt="Granid"
  width="170"
  style="display:block; border:0; outline:none; text-decoration:none;" />
```

Set only `width` (here 170px); height follows automatically. The image is
555px wide, so it stays crisp on retina down to ~180px. On a dark background
the black wordmark disappears — ask for a white variant if you need one.
