# Chord Vault v1.3 — Independent GitHub Pages PWA

This build is configured specifically for the `Guitar.github.io` repository.

Live site:
https://shannonmochizuki.github.io/Guitar.github.io/

## PWA identity

- ID: `/Guitar.github.io/`
- Start URL: `/Guitar.github.io/`
- Scope: `/Guitar.github.io/`
- Service worker scope: this repository only (`./`)
- Cache: `chord-vault-guitar-v1.3`

The service worker only removes older caches beginning with `chord-vault-guitar-`. It does not delete caches belonging to your Collection or other apps on the same GitHub Pages origin.

## Install / update

1. Upload every file in this ZIP directly to the root of the `Guitar.github.io` repository.
2. GitHub: Settings → Pages → Deploy from a branch → `main` → `/(root)`.
3. Wait for GitHub Pages to deploy.
4. Remove the previous Chord Vault shortcut/app from the phone.
5. In Chrome, open the exact live site shown above.
6. Reload the page once, then use Chrome → Install app / Add to Home screen.

Do not upload these files to `ShannonMochizuki.github.io`, `Collection`, or `Collection.github.io`.
