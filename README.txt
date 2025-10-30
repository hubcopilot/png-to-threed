# 3D Extrude Tool + GitHub Actions

### Usage
1. Enable **GitHub Pages** (Settings → Pages → Branch: `main`, root).  
2. Add a GitHub Secret named `PAT_TOKEN` with your Personal Access Token (`repo` + `workflow` scopes).  
3. Open `index.html` in your browser (from GitHub Pages).  
4. Upload a **transparent PNG**, adjust sliders, click **Export & Upload**.  
5. GitHub Actions saves the file as `models/extruded.glb`.  
6. Open `viewer.html` (on GitHub Pages) → shows the spinning model with a transparent background.  
7. Use the link in **OBS Browser Source**.

Example OBS link:  
https://<username>.github.io/3d-extrude-tool-actions/viewer.html
