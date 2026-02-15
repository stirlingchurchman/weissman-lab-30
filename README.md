# Weissman Lab: 30 Years — Reunion & Symposium

Event website for the 30th anniversary of the Weissman Lab.
June 5–6, 2026 | Cambridge, MA

## Deploying to GitHub Pages

1. Create a new GitHub repository (e.g., `weissman-lab-30`)
2. Push this folder to the repo:
   ```bash
   git init
   git add .
   git commit -m "Initial site"
   git remote add origin https://github.com/YOUR_USERNAME/weissman-lab-30.git
   git push -u origin main
   ```
3. Go to **Settings → Pages** in your GitHub repo
4. Under **Source**, select **Deploy from a branch**
5. Choose the `main` branch and `/ (root)` folder, then click **Save**
6. Your site will be live at `https://YOUR_USERNAME.github.io/weissman-lab-30/`

## Customizing Content

- **Speakers**: Edit the speaker cards in `index.html` (section `#speakers`). Replace placeholder names, affiliations, and add headshot images.
- **Gallery**: Drop photos into the `images/` folder and add `<img>` tags inside the `.gallery-grid` div, replacing the placeholder divs.
- **Schedule**: Update times and locations in the `#schedule` section.
- **Contact**: Replace placeholder organizer names and emails in the `#contact` section.

## Local Preview

Just open `index.html` in a browser — no build step required.
