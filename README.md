# IVAO Live Map

This project displays a live map of IVAO aircraft, ATC positions, and airspace boundaries using Leaflet.js and the IVAO public API.

---

## How to Use

### 1. Create a GitHub Repository
- Go to https://github.com and sign in.
- Click **+** → **New repository**.
- Name it `ivao-live-map` or any name you like.
- Select **Public** repository and create it.

### 2. Upload Files
- Upload the `index.html` file from this project to your repository.
- Commit the changes.

### 3. Enable GitHub Pages
- Go to the **Settings** tab of your repo.
- Scroll to **Pages**.
- Select branch: `main` (or `master`) and folder: `/ (root)`.
- Save.
- Your site will be available at `https://<yourusername>.github.io/<repo-name>/`.

### 4. View the Map
- Open your GitHub Pages URL in a browser.
- The map will show live IVAO aircraft, ATC markers, and sample airspace boundaries.

---

## Notes
- Data refreshes every 30 seconds.
- Airspace boundaries are sample polygons; replace with actual data as needed.
- Fully client-side; no backend needed.

---

## Optional: Push via Git Command Line

```bash
git clone https://github.com/<yourusername>/<repo-name>.git
cd <repo-name>
# Copy index.html here or edit
git add index.html
git commit -m "Add IVAO Live Map"
git push origin main
```

Replace `<yourusername>` and `<repo-name>` accordingly.
