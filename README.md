# Little Perks

This is a static HTML landing page for GitHub Pages.

## Publish to GitHub Pages

1. Push this folder to a GitHub repository.
2. In GitHub, open the repository and go to Settings > Pages.
3. Set Source to Deploy from a branch.
4. Choose the main branch and the root folder `/`.
5. Save.

Your site will be published at:

- https://<your-username>.github.io/<repo-name>/
- or https://<your-username>.github.io/ if the repo is named exactly <your-username>.github.io

## Files

- `index.html` is the homepage (About) that GitHub Pages serves.
- `perks.html` is the Little Perks referral codes page, with its search/filter/copy behaviour in a plain `<script>` at the bottom (no build step, no dependencies).
- `styles.css` holds the shared styles for both pages.
- `.nojekyll` prevents GitHub from processing the site with Jekyll.

## Local preview

Open the file directly in a browser or run:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000
