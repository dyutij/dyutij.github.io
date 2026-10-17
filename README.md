# Dyuti Jha — Jekyll Academic Website

A modern minimalist, Markdown-editable academic website for GitHub Pages.

## Publish using a NEW GitHub account

1. Sign up at https://github.com/signup and choose username `dyutijha` **if available**. If unavailable, choose another username and replace the name in the steps below.
2. Create a **public** repository named **exactly** `YOURUSERNAME.github.io` (for example, `dyutijha.github.io`).
3. Extract this ZIP on your computer. Upload **all files and folders inside** `dyuti-jekyll-starter` to the repository root. Make sure you upload the hidden `.github` folder too if using a file uploader that displays hidden files. Do **not** upload the enclosing folder or the ZIP itself.
4. Edit `_config.yml`: set `url: "https://YOURUSERNAME.github.io"` and keep `baseurl: ""`.
5. In GitHub repository **Settings → Pages**, choose **Deploy from a branch**, `main`, `/ (root)` and Save. GitHub Pages will build Jekyll automatically.
6. Wait for the Pages deployment in **Actions**, then open `https://YOURUSERNAME.github.io/`.

## Edit your site

- `index.md` — homepage
- `research.md` — research
- `publications.md` — publications (placeholder citations need replacing)
- `teaching.md` — teaching
- `cv.md` — CV page
- `contact.md` — contact details (email placeholder)
- `assets/css/style.css` — colors, typography, layout
- `_includes/nav.html` — navigation
- `_config.yml` — site URL and metadata

On GitHub, click a file → pencil icon → edit → **Commit changes**. Changes normally publish after the Pages build completes.

## CV

Upload a PDF named `Dyuti_Jha_CV.pdf` to the `files` folder. The CV page link is preconfigured to that location; until the PDF exists the link will not work.

## Notes

- This site is original and does not require a Jekyll theme, theme plugins, Node, or a local Jekyll installation.
- GitHub Pages builds it using its supported Jekyll pipeline.
- The site is intended for a **user/organization Pages repository**, not a project subdirectory. A project site needs an adjusted `baseurl`.
- Publication entries and contact details are intentionally placeholders pending verification.
