# granid-ds-dist

Public compiled distribution of the **Granid Design System**.
Generated — do not edit here. Source (private): `stefanoleone/granid-designsystem` (see its ADR 0005).

Consume by pinning a versioned asset from a [Release](https://github.com/stefanoleone/granid-ds-dist/releases):

```
https://github.com/stefanoleone/granid-ds-dist/releases/download/<tag>/granid-web.css
```

`manifest.json` (published with each release) carries the `sha256` and an `sha384` (SRI) `integrity` value for the pin.

Releases are cut by CI in the source repo (`.github/workflows/publish-dist.yml`). Do not commit here by hand.
