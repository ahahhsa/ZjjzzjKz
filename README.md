# ZjjzzjKz

This repository contains a simple GitHub Pages site in the `docs/` folder.

Site URL: https://ahahhsa.github.io/ZjjzzjKz

How to publish

- Commit and push changes to the `main` branch. The workflow at `.github/workflows/pages.yml` will publish the contents of `docs/`.

Example:

```bash
git add docs README.md .github/workflows/pages.yml
git commit -m "Add GitHub Pages site"
git push origin main
```

If Pages doesn't appear automatically, open the repository Settings → Pages and ensure GitHub Pages is configured to use the GitHub Actions deployment. The URL above will remain the same.
