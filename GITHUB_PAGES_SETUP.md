# MSS Club Management Suite Demo v0.65

## Camera
Use the HTTPS GitHub Pages address in current Chrome or Edge.
At Check-In, click **Take Photo**. The app now uses explicit camera controls and a broad `video:true` request for maximum laptop/Chromebook compatibility.

If Chrome asks for camera permission, choose **Allow**.
If blocked: site controls/lock icon → Site settings → Camera → Allow, then reload.

## Full Backup / Restore
The Workflow Dashboard and Setup page now include:
- **Download Full Backup**
- **Restore Full Backup**

The JSON backup contains the entire current Club Manager state, including registrations, check-ins, evaluations, teams, offers, payments, documents, and settings. This is the recommended way to move working data between browsers/computers while the prototype still uses browser storage.

## GitHub update
Upload/replace `index.html` and the supporting files in the repository root and commit. GitHub Pages will republish automatically.
