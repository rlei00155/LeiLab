Lab Website
===========

Static lab website inspired by `https://yiquan2.com/Lab-Page/`.

Local Development
-----------------

- Open `index.html` in a browser, or serve locally:

```bash
python -m http.server 8000
# or
npx serve . -l 8000 --single
```

Repository Structure
--------------------

```
.
├── index.html
├── assets/
│  ├── css/
│  │  └── styles.css
│  └── images/
└── .github/
   └── workflows/
      └── pages.yml
```

Deploy with GitHub Pages
------------------------

1. Push this repo to GitHub.
2. Ensure Actions are enabled.
3. The `pages.yml` workflow publishes the site to GitHub Pages on push to `main`.
4. In Settings → Pages, set Source to GitHub Actions.

Customize Content
-----------------

- Update section content in `index.html`.
- Replace placeholder images in `assets/images/`.
- Adjust theme colors and spacing in `assets/css/styles.css`.

License
-------

MIT


