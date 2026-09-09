# DAF-TCCC-WEB v2.21.0-web.1 Deployment

## One-time GitHub Pages setup

This web app is a static site. No build workflow is required.

1. Open the `DAF-TCCC-WEB` repository on GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Branch: **main**.
5. Folder: **/(root)**.
6. Click **Save**.

Once configured, commits pushed to `main` publish automatically.

## Remove obsolete Actions workflows

If an older `.github/workflows/pages.yml` or any APK/Android workflow still exists in the web repository, delete it. This baseline intentionally uses no custom Pages workflow, avoiding Node/npm/Gradle dependencies and `configure-pages` setup failures.

## Expected site

`https://afomsteam.github.io/DAF-TCCC-WEB/`

After deployment, verify the home screen reports **v2.21.0-web.1**. Refresh once after publishing; an installed PWA may need to be fully closed and reopened so the new service worker/cache takes control.
