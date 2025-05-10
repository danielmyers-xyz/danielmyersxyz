# danielmyers.xyz

This is the source code for my personal website, built with [Hugo](https://gohugo.io/) using the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme. The site is deployed via [Cloudflare Pages](https://pages.cloudflare.com/) and served at [https://www.danielmyers.xyz](https://www.danielmyers.xyz).

## 🧭 About

I'm Daniel Myers — a GIS engineer focused on workflow automation, public-sector innovation, and field-ready geospatial solutions. This site showcases my professional experience, project writeups, and experiments with open-source spatial technology.

## 🚀 Features

- Hugo static site generator with PaperMod theme
- GitHub-hosted zoning lookup and other JS-based tools
- Posts about GIS workflows, data apps, and spatial automation
- Deployed using Cloudflare Pages with Git-based CI/CD

## 📁 Structure

```
.
├── content/           # Pages and posts
├── layouts/           # Custom layout overrides
├── static/            # Static assets like images
├── themes/            # PaperMod as a Git submodule
├── config.toml        # Site configuration
└── README.md
```

## 📦 Development

To run locally:

```bash
git clone https://github.com/danielmyers-xyz/danielmyersxyz.git
cd danielmyersxyz
hugo server -D
```

Then open `http://localhost:1313` in your browser.

## 🌐 Deployment

This site is automatically deployed via Cloudflare Pages when changes are pushed to the `main` branch.

## 📸 License

Content © Daniel Myers. Code and configurations are open-source under the MIT License unless otherwise noted.
