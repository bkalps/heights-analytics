# Heights Analytics — GitHub Pages starter

This is a plain HTML/CSS/JavaScript starter for the Heights Analytics homepage.

## Structure

```text
heights-analytics-site/
├── index.html
├── styles.css
├── script.js
├── README.md
└── assets/
    └── logo.svg
```

## Preview locally

You can simply open `index.html` in a browser.

For a local server (recommended), from this folder run:

```bash
python3 -m http.server 8000
```

Then visit:

`http://localhost:8000`

## Publish with GitHub Pages

1. Create a GitHub repository, for example `heights-analytics`.
2. Upload the contents of this folder to the repository.
3. In GitHub, open **Settings → Pages**.
4. Set the source to deploy from the `main` branch and `/ (root)`.
5. GitHub will provide a `github.io` URL.
6. Once the site is ready, connect your Squarespace-registered domain under the repository's Pages settings.

### Custom domain

Do not add a `CNAME` file yet because the final domain name has not been provided in this project. Once you give me the domain, I can create the correct CNAME file and walk you through the DNS records at Squarespace.

## Notes

- The contact email is currently a placeholder: `hello@heightsanalytics.com`.
- The blue-tile pattern is CSS/SVG-based, so no stock-image dependency is required.
- All layout styles are responsive for phones, tablets, and desktop.
