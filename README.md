# Veya Static Support Site

Static support and policy pages for Veya, published with GitHub Pages.
The support, privacy and terms pages provide Turkish / English language switching;
the separate about page is in Turkish.

[View the support site](https://kadir2848.github.io/veya-support/)

Bu depo, Veya'nın destek, gizlilik, kullanım koşulları ve uygulama bilgilerini
barındıran statik sitesidir. Ana uygulama veya sunucu kodunu içermez.

## What it provides

- Support and abuse-reporting contact links.
- Privacy policy and terms pages with browser-side language switching.
- A separate page describing the Veya app.

This repository contains the public website. The Veya application, account system
and backend are outside its scope; the site itself does not implement those features.

## Run locally

Clone the repository and open `index.html` in a browser. No package installation or build step is needed.

For a local HTTP preview, if Python 3 is installed:

```sh
git clone https://github.com/kadir2848/veya-support.git
cd veya-support
python3 -m http.server 8000 --bind 127.0.0.1
```

Open <http://127.0.0.1:8000>. Stop the server with `Ctrl+C`.

## Files and technologies

| File | Purpose |
| --- | --- |
| `index.html` | Support home page and contact links. |
| `privacy.html` | Privacy policy in Turkish and English. |
| `terms.html` | Terms of use in Turkish and English. |
| `about.html` | Turkish app information page. |
| `styles.css` | Shared styles for the support and policy pages. |

Built with HTML, CSS and inline JavaScript for language switching. GitHub Pages
serves the site from the root of the `main` branch.
