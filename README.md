# Tan Zhi Xiang | Portfolio

A static portfolio website (plain HTML, CSS and JavaScript, no build step).

## Files

- `index.html`: the whole site
- `assets/img/`: project photos and slides
- `assets/vid/`: project videos and their preview images
- `.nojekyll`: tells GitHub Pages to serve the files as they are

## Put it online with GitHub Pages

1. On github.com, click **New repository**. Name it `YOUR-USERNAME.github.io` to get the address `https://YOUR-USERNAME.github.io`, or any other name (for example `portfolio`) to get `https://YOUR-USERNAME.github.io/portfolio`.
2. Open the new repository, click **Add file > Upload files**, and drag in `index.html`, `.nojekyll` and the whole `assets` folder. Wait until every file has finished uploading, then click **Commit changes**.
3. Go to **Settings > Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose the `main` branch and the `/ (root)` folder, and click **Save**.
4. Wait a minute or two, then open the address shown at the top of the Pages settings.

## Editing later

- Project text, categories and order are in the `P` list near the bottom of `index.html`.
- To add a project, copy one entry in that list, change the text, and put its photos in `assets/img/`.

## Managing projects from the browser

Open `admin.html` (for example `https://YOUR-USERNAME.github.io/portfolio/admin.html`). It is hidden from search engines and does nothing without a GitHub token. Create a fine-grained token at github.com > Settings > Developer settings > Personal access tokens, limited to this repository with **Contents: Read and write**, and paste it into the page once. The page lists your projects: add a new one, edit any field (title, category, description, "More details" sections, photos and videos, cover), delete one, or reorder them. Every save is committed to the repository and the site updates itself.
