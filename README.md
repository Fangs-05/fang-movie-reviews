# FANG

A classic-theatre movie review app: star ratings, quick reviews, genre lists, Top 10,
similar-movie suggestions, personalised lists, and an admin panel with Excel export.

Single static file (`index.html`), no build step.

## Deploy on GitHub Pages
1. Create a repository and push these files to the `main` branch.
2. In the repo go to **Settings → Pages → Build and deployment → Source** and choose **GitHub Actions**.
3. Push (or run the workflow from the **Actions** tab). The site appears at
   `https://<your-username>.github.io/<repo-name>/`.

## Admin
Sign in with `admin` / `admin123`, open **Backstage**, and use **Download as Excel**.

## Notes
- Data is stored in each visitor's browser (localStorage), so it is not shared between devices.
- The admin password is visible in the page source. Replace it with a real backend before public use.
