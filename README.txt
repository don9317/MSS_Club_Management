MSS Club Management Suite Demo v0.63 — Tryout Day Camera + Permanent Team Delete

HEADSHOT / CAMERA
- Check-In now provides separate Take Photo and Upload buttons.
- Take Photo opens an in-app webcam window using the laptop/tablet/phone camera.
- Capture & Save attaches the photo directly to the selected player.
- Camera stream is stopped immediately when the photo is saved or the window is closed.
- Upload remains available as a fallback.
- If browser camera permission is blocked or unavailable, the app explains the issue and offers Upload instead.

PERMANENT TEAM DELETE
- Deleted teams now receive a persistent tombstone containing grade + team name.
- Future data migrations/reconciliation will not automatically recreate a deliberately deleted team.
- Unlinked Team Data ignores tombstoned teams.
- Explicitly creating the same team again in Team Setup removes the tombstone and intentionally restores it.

NOTE
- A team deleted in an older version before v0.63 did not have a tombstone. If it reappears on the first v0.63 load, delete it once in v0.63; subsequent versions will preserve that deletion.

Existing v0.62 data migrates automatically.
