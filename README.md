# YJ Research Notes

Personal research site, built with Jekyll and hosted on GitHub Pages.

## Upload
1. Upload every file and folder in this bundle to the root of your repo, including the hidden `.pages.yml`. On GitHub web, drag the folder contents into "Add file > Upload files".
2. Repo **Settings > Pages**: Source = "Deploy from a branch", Branch = `main`, folder = `/ (root)`. Save.
3. If the repo is NOT named `<username>.github.io`, open `_config.yml` and set `baseurl: "/<repo-name>"`.
4. Wait 1–2 minutes, then open the URL shown in Settings > Pages.

## Write and edit notes (only you)
1. Go to https://app.pagescms.org and sign in with GitHub.
2. Install/authorize it for this repo only.
3. Open the repo > Notes > Add an entry: title, date, body. Save.
4. The site rebuilds automatically in 1–2 minutes.

Only accounts with write access to this repo can edit. Do not add collaborators.

## Files
- `index.html`: Home
- `notes/index.html`: Notes list (newest first)
- `_posts/`: your notes, one Markdown file each (`YYYY-MM-DD-title.md`)
- `_layouts/`: page templates
- `assets/style.css`: all styling
- `assets/images/`: images uploaded via Pages CMS
- `.pages.yml`: editor configuration for Pages CMS
