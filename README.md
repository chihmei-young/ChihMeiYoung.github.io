# Chih-Mei Young — Portfolio

A responsive, dependency-free portfolio built with HTML, CSS, and JavaScript.

## Preview locally

Open `index.html` directly in a browser, or run the following from this directory:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000` in your browser. Stop the server with Ctrl+C.

## Customize

- Edit biography, research, projects, education, and contact details in `index.html`.
- Replace the hero SVG and project illustration blocks with your own images. The project notes are intentionally labeled placeholders; expand them with results and links.
- Change the color and font variables at the top of `style.css`.
- Replace `assets/chih-mei-young-resume.pdf` when your resume changes. The included PDF is the supplied resume, including its contact and reference details; review it before publishing.
- Education dates reflect the supplied resume; update the doctoral status when needed.

No external fonts, image services, backend, package installation, or build step are required. Contact uses an email link and opens the visitor's mail application.

## GitHub Pages

Commit and push these files to the repository. Under **Settings → Pages**, choose **Deploy from a branch**, then select **main** and **/(root)** and save. Keep `index.html`, `style.css`, and `script.js` at the repository root and include `assets/`. All local paths are relative, so the site also works under a GitHub Pages project path.
