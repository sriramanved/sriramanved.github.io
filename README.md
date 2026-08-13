# Ved Sriraman — Personal Research Website

A lightweight static academic website designed for GitHub Pages.

## Files

- `index.html` — all page content
- `styles.css` — all styling
- `assets/` — put your photo and CV here

## Customize first

Search `index.html` for these placeholders and replace them:

- `YOUR_EMAIL@columbia.edu`
- `YOUR_GOOGLE_SCHOLAR_URL`
- `YOUR_GITHUB_URL`
- `ADVISOR_URL`
- `#` links on papers/projects
- placeholder author lists and project descriptions

### Add your photo

Put your photo at:

`assets/profile.jpg`

Then in `index.html`, replace:

```html
<div class="portrait-placeholder">
  <span>your photo</span>
</div>
```

with:

```html
<img class="portrait" src="assets/profile.jpg" alt="Ved Sriraman" />
```

### Add your CV

Put your CV at:

`assets/ved-sriraman-cv.pdf`

The existing CV link will then work automatically.

## Preview locally

Simplest option: double-click `index.html`.

For a local web server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## GitHub Pages

1. Create a public GitHub repository named exactly:
   `YOUR_GITHUB_USERNAME.github.io`
2. Upload these files or push them with git.
3. Open the repository on GitHub.
4. Go to **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch **main** and folder **/(root)**.
7. Save.
8. Your website will appear at:
   `https://YOUR_GITHUB_USERNAME.github.io`

## Optional custom domain

Later, you can buy a domain like `vedsriraman.com` and point it to GitHub Pages.
There is no need to do this initially.
