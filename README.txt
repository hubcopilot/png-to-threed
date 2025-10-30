3D Extrude Tool + GitHub Actions
=================================

Usage:
1. Enable GitHub Pages on this repo (branch=main, root).
2. Open index.html (from Pages or locally).
3. Upload a transparent PNG, adjust sliders, click "Export & Upload".
4. The file is base64-encoded and sent to a GitHub Actions workflow.
5. Workflow saves it as models/extruded.glb and commits to repo.
6. viewer.html always loads the latest extruded.glb.
7. Use: https://<username>.github.io/3d-extrude-tool-actions/viewer.html in OBS Browser Source.

Setup:
- Create a GitHub PAT with workflow + repo scope.
- Replace YOUR_USERNAME and YOUR_PAT_WITH_WORKFLOW_SCOPE in index.html.
- (Optional: use a proxy or secrets for safer token handling).