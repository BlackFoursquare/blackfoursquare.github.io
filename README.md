# Black 4 Square website

A static site for GitHub Pages with no build step and no JavaScript.

## Deploy on GitHub Pages

1. Copy the contents of this folder into a GitHub repository.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the branch containing these files and the `/ (root)` folder, then save.

The site uses relative asset paths, so it works both at a custom domain and at a project URL such as `username.github.io/repository-name/`.

## Files

- `index.html` — page structure and copy
- `styles.css` — responsive layout and visual design
- `assets/` — logo (`logo.webp`, `logo-512.png`) and locally hosted Google Play artwork

Fonts (Anton, Barlow, Barlow Condensed) load from Google Fonts, with system fallbacks. Each game links to its Google Play page and to its WebGL build on `daniildenysov.github.io`.
