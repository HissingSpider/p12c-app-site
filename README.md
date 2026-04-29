# GitHub Pages Export

This folder is safe to publish by itself. It contains only the public App Store support site and does not include your app source code.

Files:

- `index.html`
- `privacy.html`
- `support.html`
- `.nojekyll`

Recommended publish path:

1. Create a separate public GitHub repository such as `p12c-app-site`.
2. Copy only the contents of this folder into that repo.
3. Push to `main`.
4. In GitHub, open `Settings` -> `Pages`.
5. Set `Build and deployment` to `Deploy from a branch`.
6. Select branch `main` and folder `/ (root)`.

Your final URLs will look like:

- `https://<github-username>.github.io/<repo-name>/`
- `https://<github-username>.github.io/<repo-name>/privacy.html`
- `https://<github-username>.github.io/<repo-name>/support.html`

If you later attach a custom domain, use that domain in App Store Connect instead.

Important:

- Do not publish the main Pocket12c app repository if you want to keep the app code private.
- Publish this folder from a separate repo, or from an orphan branch that contains only these files.
