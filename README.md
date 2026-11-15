# CPM 2 Game Guardian Pro — preview project

This is a starter project containing:
- A responsive website/PWA interface in `web/`.
- A native Android WebView wrapper in `app/`.
- A GitHub Actions workflow that builds a debug APK and uploads it as an artifact.

## Important limitations
This preview does **not** connect to Car Parking Multiplayer 2, collect game passwords, or modify game data. The operation buttons are intentionally disabled. Genuine account changes require an official developer-approved authentication and modification interface, its documentation, and permission scope. Do not add password collection or unofficial credential handling.

## Build the APK with GitHub
1. Create a GitHub repository and upload the contents of this folder.
2. Open the repository's **Actions** tab.
3. Run **Build Android APK** (or push to `main`).
4. Open the completed workflow run and download the `CPM2-Game-Guardian-Pro-preview` artifact.
5. Unzip the artifact to get `app-debug.apk`.

## Website
Publish the contents of `web/` using GitHub Pages (Settings → Pages → deploy from branch; select `/web` if using a suitable publishing workflow, or copy its contents to the publishing root). The site is a preview interface only.

## Next integration requirements
Obtain from the game developers: supported sign-in/OAuth flow, API base URL, endpoint documentation, authorization scope, test environment, rate limits, and a way to verify the authoritative account state.
