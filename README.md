# granid-ds-dist

Public compiled distribution of the **Granid Design System**.
Generated — do not edit here. Source (private): `stefanoleone/granid-designsystem` (see its ADR 0005).

Pin a versioned asset from a [Release](https://github.com/stefanoleone/granid-ds-dist/releases):

```
https://github.com/stefanoleone/granid-ds-dist/releases/download/v1.1.0/granid-web.css
```

Current: **v1.1.0**. Files in this branch track the latest release; `manifest.json`
carries the `sha256` and an `sha384` (SRI) `integrity` value for the pin.

Releases are cut by CI in the source repo (`.github/workflows/publish-dist.yml`).
Do not commit here by hand.

## Brand assets

[`brand/`](brand/) holds static brand artifacts (logos) with stable,
hotlinkable raw URLs — referenced by `main`, not release-pinned (a logo is not
a semver'd surface). See [`brand/README.md`](brand/README.md). Also generated
from the private source (ADR 0005, 2026-07-17 amendment).
