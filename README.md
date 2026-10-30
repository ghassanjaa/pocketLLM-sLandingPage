# PocketLLM — GitHub Pages Website

Landing page, Privacy Policy, and Terms of Service for **PocketLLM** (com.ghassanjaam.PocketLLM).

## Files

| File | Purpose |
|---|---|
| `index.html` | Landing page with hero and feature highlights |
| `privacy.html` | Full Privacy Policy (required for App Store) |
| `terms.html` | Terms of Service |
| `style.css` | Shared stylesheet (dark mode, responsive) |
| `_config.yml` | GitHub Pages / Jekyll configuration |

## Deploy to GitHub Pages

1. Push this folder's contents to the **root** of your GitHub repository's `main` branch.
2. In your repository on GitHub, go to **Settings → Pages**.
3. Under **Source**, select **Deploy from a branch**, choose `main`, and set the folder to `/ (root)`.
4. Click **Save**. GitHub will build and publish the site within a minute or two.

### Your URLs will be:

```
https://<your-github-username>.github.io/<repo-name>/
https://<your-github-username>.github.io/<repo-name>/privacy.html
https://<your-github-username>.github.io/<repo-name>/terms.html
```

Use the **Privacy Policy URL** (`/privacy.html`) in your App Store Connect app listing under **App Privacy → Privacy Policy URL**.

## Local Preview

No build step required — open `index.html` directly in any browser, or serve with:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Contact

Ghassan Jaam — gassanjaam@gmail.com
