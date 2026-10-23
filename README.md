# KonniConsult – ITSM Solutions Website

Official website for **KonniConsult**, an IT service management (ITSM) company based in Dar es Salaam, Tanzania. A static, responsive website built with HTML, CSS and JavaScript (Bootstrap 5).

## Pages

| Page | File |
|------|------|
| Home | `index.html` |
| About | `about.html` |
| Services | `service.html` |
| IT Consulting | `consult.html` |
| Cloud Solutions | `cloud.html` |
| Email Solutions | `email.html` |
| GIS Solutions | `GIS.html` |
| Repair & Maintenance | `repair.html` |
| Relocation | `relocation.html` |
| Blog | `blog.html` |
| Get a Quote | `quote.html` |
| Contact | `contact.html` |

## Project Structure

```
konniconsult/
├── index.html          # Home page (site entry point)
├── *.html              # Other pages
├── assets/
│   ├── css/            # Bootstrap + custom styles
│   ├── js/             # Custom scripts
│   ├── img/            # Images, logo and video
│   └── lib/            # Third-party libraries (animate, easing, wow, waypoints)
├── .nojekyll
├── .gitignore
├── LICENSE.txt
└── README.md
```

## Run Locally

No build step is required. Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Deploy on GitHub Pages

1. Push the project to the `main` branch.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/ (root)`, then save.
4. The site will be published at `https://<username>.github.io/konniconsult/`.

## Credits

Based on the *HighTech – IT Solutions* template by [HTML Codex](https://htmlcodex.com), used under its license (see `LICENSE.txt`).
