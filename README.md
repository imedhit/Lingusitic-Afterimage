# Ec(ak)ou: Ghost Speech Cartography

Interactive speculative cartography of Bengaluru exploring human-only languages, clandestine signal trails, and spaces shielded from AI surveillance (2026–2050).

---

## Publish on GitHub Pages

The included GitHub Actions workflow builds and deploys the site whenever you push to `main` or `master`. Visitors do not need to install Node.js or run any commands.

### One-time setup

1. Upload or push the project files to a GitHub repository on the `main` or `master` branch.
2. In that repository, open **Settings → Pages** and set **Build and deployment → Source** to **GitHub Actions**.
3. Open the **Actions** tab and wait for the **Deploy to GitHub Pages** workflow to finish.

After deployment, the Pages URL appears in the workflow run and in **Settings → Pages**. For a regular repository, it is usually `https://<owner>.github.io/<repository>/`.

The workflow rebuilds and republishes the site on each subsequent push to `main` or `master`. You can also start a deployment manually from **Actions → Deploy to GitHub Pages → Run workflow**. The checked-in `assets` and `docs` folders are not needed for this Actions-based deployment; the workflow publishes the generated `dist` site.
