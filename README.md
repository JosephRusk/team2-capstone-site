# Drone-Mounted Emergency Communication System — Team 2

Capstone project website. Static site: `index.html` + `styles.css` + `images/`.

## Publish it with GitHub Pages

1. **Create the repository**
   - Go to github.com and click **New repository**.
   - Name it anything you like (e.g. `team2-capstone-site`). Keep it Public. Don't add a README/gitignore/license (you already have files).
   - Click **Create repository**.

2. **Upload these files**
   - On the new repo's page, click **Add file → Upload files**.
   - Drag in `index.html`, `styles.css`, and the whole `images` folder (with all 6 photos inside).
   - Scroll down and click **Commit changes**.

   *(If you'd rather use git from the command line instead of the browser upload, unzip this folder locally and run:)*
   ```
   git init
   git add .
   git commit -m "Initial capstone site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-repo>.git
   git push -u origin main
   ```

3. **Turn on GitHub Pages**
   - In your repo, go to **Settings → Pages** (left sidebar).
   - Under "Build and deployment" → **Source**, choose **Deploy from a branch**.
   - Under **Branch**, choose `main` and folder `/ (root)`, then click **Save**.
   - Wait about 1 minute, then refresh the page — GitHub will show your live URL, typically:
     `https://<your-username>.github.io/<your-repo>/`

4. **Share the link** — that URL is your live capstone site. Any time you push new changes to `main`, the site updates automatically within a minute or two.

## Making updates later

- To change a bio or swap a photo, edit `index.html` (or replace the file in `images/`) and re-upload/commit. GitHub Pages will redeploy automatically.
- Each team member's photo file is referenced by name in `index.html` — keep filenames the same, or update the `src` path if you rename a file.

## File structure

```
.
├── index.html       # Page content (title, team number, member cards)
├── styles.css        # All styling
├── images/           # Headshots (already cropped/compressed for web)
└── README.md
```
