# Jingzhou Shen Academic Website

This is a full Jekyll / GitHub Pages academic homepage in the style of Academic Pages / Minimal Mistakes-based academic websites.

## Deploy on GitHub Pages

1. Create or open the repository `NorahCadeJS.github.io`.
2. Upload all files in this folder to the repository root.
3. Go to **Settings → Pages**.
4. Choose **Deploy from a branch**.
5. Select `main` branch and `/ (root)`.
6. Wait for GitHub Pages to build and publish the site.

## Local Preview

```bash
bundle install
bundle exec jekyll serve
```

Then open `http://localhost:4000`.

## Editing

- Main homepage text: `index.md`
- Research page: `_pages/research.md`
- Publications: `_publications/*.md`
- Experience and awards: `_pages/experience.md`
- CV file: `assets/files/JingzhouShen_CV.pdf`
- Navigation: `_data/navigation.yml`
- Basic profile information: `_config.yml` and `_data/profile.yml`
