# Clearframe V11 — GitHub Pages PWA installation

This ZIP is a **ready-to-publish static website**. It needs no npm, build process, database or secret keys. It contains 29 routines, 177 subroutines and 357 perspective-reversible indicators.

## Put V11 on GitHub Pages

1. Create a new repository at GitHub (for example `clearframe-v11`). A public repository is simplest for a public Pages website.
2. Extract `clearframe-v11-github-pages.zip` on your computer.
3. In the new repository, choose **Add file → Upload files**. Upload the **contents** of the extracted folder, including `index.html`, `sw.js`, `manifest.webmanifest`, all `.js`, `.css` and icons. Do not upload the ZIP as a single file, and do not place everything in an extra nested folder.
4. Commit the uploaded files to the `main` branch.
5. Open the repository's **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, then save.
6. Open the Pages URL that GitHub shows when the site is ready. For a standard project repository, it has the form `https://USERNAME.github.io/REPOSITORY/`.
7. In Chrome or another PWA-capable browser, use its **Install app** action. On iPhone/iPad, use Safari's **Add to Home Screen** action where available.

### Confirm it is the right build

The home screen must show **V11 · 15 chapters mapped** and the counts **29 routines / 177 subroutines / 357 reality signals**. Verify the **Book 1 source map** has 16 sections. Test the **Process an emotion** workflow: enter a situation, confirm the matches at or above 1% are grouped by control routine and ordered by combined score, select an observation in Step 3, and tap **Swap Shoes** twice. The pronouns should reverse and return while the selected indicator and synthesis remain unchanged.

To test offline use, **first visit online** so the service worker caches the assets, then disconnect and reopen the installed app. The first offline visit cannot work before the cache is installed.

### Privacy and updates

- Your entries and saved moments remain in the **local browser storage for each origin**. The ChatGPT-hosted version and your `github.io` version do **not** share stored moments. Export and import through Clearframe if you want to transfer your saved entries.
- Avoid clearing site data without exporting a backup. Uninstalling an app or clearing a browser profile may remove saved local information.
- A new repository URL avoids old version caches. If you later update V11 on GitHub, adjust the asset query version in `index.html` and the cache version/assets in `sw.js` to force asset replacement.
- GitHub Pages must be enabled; simply viewing `index.html` locally through `file://` does not provide a working installable PWA or service worker.
- This is an educational, original conceptual adaptation of family-therapy ideas, **not a diagnostic, therapy, safety-assessment, or clinically validated tool**.

The included `book1-v10-source-ledger.json` records chapter/page provenance and original editorial mapping decisions for review.
