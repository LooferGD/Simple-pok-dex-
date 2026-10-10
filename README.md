# Simple Pokédex

A mobile-first Pokémon binder tracker with a dark theme and #00c8ff accents.

## Upload to GitHub Pages

1. Unzip this download.
2. On GitHub, create a public repository named `simple-pokedex`.
3. Choose **Add file → Upload files**.
4. Upload `index.html` to the repository's top level. You can also upload the included README, artwork sources, and `.nojekyll` file. Do not upload the ZIP itself or put index.html inside another folder.
5. Commit the upload to the `main` branch.
6. Open **Settings → Pages**.
7. Under **Build and deployment**, choose **Deploy from a branch**.
8. Select **main** and **/(root)**, then click **Save**.
9. Once GitHub finishes publishing, open the site address shown there: `https://YOUR-USERNAME.github.io/simple-pokedex/`.

Official setup reference: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Move your existing collection

This copy starts empty. On your existing Dex Pocket site, press **Export .txt**. Open Simple Pokédex on the device you plan to use, press **Import .txt**, select the exported file, review it, then add the copies.

Import adds to the displayed collection. Importing the same file again adds its copies again, so import once when moving an existing collection.

## Saving and backups

Your collection saves automatically in this browser on this device. There is no account, backend or cross-device synchronization. Clearing site/browser data removes your collection, and private browsing may discard it. Keep a text export as a backup. Using a different browser, GitHub address or device creates a separate collection.

## Included features

- Add, All, Owned and Missing tabs.
- Search by Pokédex number or name.
- All 1,025 Pokémon with full-colour artwork and solid grey silhouettes for missing entries.
- Page, side, pocket and slot information.
- Front pockets count left to right; back pockets count right to left, with 1 at top right and 9 at bottom left.
- Copy counts with +/− buttons and an undo button after adding.
- Text export: `0001 - Bulbasaur`, one line per copy.
- Text import: numbers separated by commas, line breaks or other text, with a review before adding. Numbers outside 1–1025 and digits embedded in names such as Porygon2 are ignored. Maximum import size: 5 MB.

## Files

`index.html` contains the complete working site: its code, styles, icons and all Pokémon images. There is no installation or build step. It is approximately 17 MB because every image is included. The other files provide documentation and attribution.

You can also open index.html locally for a preview. Move your collection using text export/import when switching from the local file to the published URL, because browsers store those separately.

Pokémon artwork and names are attributed in ARTWORK-SOURCES.txt. Pokémon belongs to its respective rights holders; this is an unofficial personal collection tool.
