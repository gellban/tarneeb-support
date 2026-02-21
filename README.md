# Tarneeb Master – Support Website

This repository hosts the **GitHub Pages** support website for the iOS game **Tarneeb Master**.

## Files

| File | Purpose |
|------|---------|
| `index.html` | Main support page (title, contact, FAQ, how to get help) |
| `styles.css` | Clean, minimal CSS styles optimised for mobile viewing |

## Enabling GitHub Pages

1. Open the repository on GitHub.
2. Go to **Settings** → **Pages** (left sidebar).
3. Under **Source**, select the branch you want to publish (e.g. `main`) and choose **/ (root)** as the folder.
4. Click **Save**.
5. GitHub will display the live URL – typically `https://<username>.github.io/<repository>/`.
6. Use that URL as the **Support URL** in App Store Connect for your app listing.

## Local Preview

You can preview the page locally without any build tools:

```bash
# Python 3
python3 -m http.server 8080
# then open http://localhost:8080 in your browser
```