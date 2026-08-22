MSS Club Management Suite Demo v0.66

CAMERA HOTFIX
- Fixed the v0.65 error: "Camera window could not be initialized."
- The webcam modal had accidentally been embedded inside the Print Receipt HTML template rather than the actual page DOM.
- Webcam window is now real page markup and can open from Check-In.
- Added a self-repair fallback that recreates the webcam dialog if its markup is ever missing.

FULL BACKUP / RESTORE from v0.65 is retained.
Existing v0.65 data migrates automatically.
