# MSS Club Management Suite Demo v0.64

## Recommended Chromebook Use

For the live **Take Photo** feature, serve this app from an HTTPS site. GitHub Pages is the easiest option.

### GitHub Pages setup
1. Create a GitHub repository (for example: `mss-club-manager-demo`).
2. Upload the files from this folder to the repository root:
   - `index.html`
   - the CSV and spreadsheet support files
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/(root)**
5. Click **Save**.
6. GitHub will provide an HTTPS web address. Open that address in Chrome on the Chromebook.
7. When you click **Take Photo**, Chrome should ask for camera permission. Choose **Allow**.

### Chromebook camera permission
If the camera is blocked:
- Click the lock/site-controls icon next to the web address.
- Open **Site settings**.
- Set **Camera** to **Allow**.
- Reload the page.

## Important
Opening `index.html` directly from the Chromebook Files/Downloads app uses a local `file://` address. Live webcam access is normally blocked there. The app will now display an explicit message instead of failing silently.

All other v0.63 functionality is retained, including permanent team deletion tombstones.
