# Fariha's Birthday Surprise
A small Bengali birthday mini-game website and Android WebView app.

## Website preview
Open `index.html` in a browser, or publish the repository with GitHub Pages (Settings → Pages → Deploy from branch → main → /(root)).

## Build Android APK with GitHub Actions
1. Create a GitHub repository and upload all files in this folder (not the ZIP itself).
2. Make sure the workflow is at `.github/workflows/build-apk.yml`.
3. Open Actions → Build Fariha Birthday APK → Run workflow.
4. When complete, open the workflow run and download the `Fariha-Birthday-APK` artifact.
5. Extract the downloaded artifact ZIP to get `app-debug.apk`.

This is an unsigned debug APK for testing. It contains a WebView wrapper around the included offline game. The birthday story is an animated in-page story, not a prerecorded MP4. The decorative cover is drawn with CSS and works offline.
