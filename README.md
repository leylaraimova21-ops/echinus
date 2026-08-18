# Echinus — portfolio site

## Structure
- `index.html` — the site itself
- `models/` — put your exported `.glb` files here
- `assets/` — put photos, renders, and other images here

## To replace the placeholder 3D model
1. Export your model from Blender as `.glb` (File → Export → glTF 2.0)
2. Drop the file into `models/`, e.g. `models/echinus-capital.glb`
3. In `index.html`, find the `<model-viewer>` tag and change `src="..."` to
   `src="models/echinus-capital.glb"`

## To publish on GitHub Pages
1. Create a new repository on github.com (public, no README needed — we already have one)
2. Upload all files from this folder into it (drag and drop on the repo page, or use git)
3. Go to the repo's Settings → Pages
4. Under "Source", choose the `main` branch and `/ (root)` folder, then Save
5. Your site will be live in a minute or two at `https://<your-username>.github.io/<repo-name>/`
