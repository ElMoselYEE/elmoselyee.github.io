# elmoselyee.github.io

This is the source code for [blaynemoseley.com](https://www.blaynemoseley.com).

The site is a single static page, `docs/index.html`, styled like a code editor. Each role on the resume is a file
written in the language used most in that job. [GitHub Pages](https://pages.github.com/) serves the `docs/` folder
from `main` as-is (`docs/.nojekyll` turns off the Jekyll build).

# Usage

Open `docs/index.html` in a browser, or serve the folder:

    python3 -m http.server -d docs 4000

The resume content lives in the `FILES` and `COMMITS` objects near the top of the page's script.

# Deploy

Merge to `main`. GitHub Pages publishes it automatically.

# Paths

- `/` is the site.
- `/resume/download` redirects to the PDF resume.
