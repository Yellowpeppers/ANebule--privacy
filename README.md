# ANubela Privacy Site

This folder contains a static web page for hosting ANubela's privacy policy on GitHub Pages (or any static host). To publish:

1. Create a new GitHub repository (for example `anubela-privacy`).
2. Copy the contents of this `privacy-site` directory into the repository.
3. Commit and push.
4. In GitHub, open **Settings → Pages**, choose “Deploy from branch”, select the `main` branch and root (`/`) folder, then save.
5. GitHub Pages will generate a URL such as `https://<username>.github.io/anubela-privacy/`. Use this link in App Store Connect and inside the app.

If you later update the privacy policy text, edit `index.html`, commit, and push again—Pages will redeploy automatically.
