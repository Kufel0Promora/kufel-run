# Kufel Run website

Static landing page for the Android game Kufel Run. Designed for GitHub Pages.

## Publish with GitHub Pages
1. Create a new public repository on GitHub (for example `kufel-run`).
2. Upload `index.html` and `favicon.svg` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then Save.
6. Wait for GitHub Pages to publish the site. The address will look like:
   `https://YOUR-USERNAME.github.io/kufel-run/`

## Add your APK download
The download button currently has a placeholder link (`href="#"`).
The recommended option is to upload your APK to a GitHub Release:
1. Open the repository's **Releases** section and create a release.
2. Attach the APK file as a release asset.
3. Publish the release.
4. Replace `href="#"` on the `DOWNLOAD FOR ANDROID` button in `index.html` with the direct APK asset URL or the release page URL.

The site is static; it does not need a separate server or database.
