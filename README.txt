MSS Club Management Suite Demo v0.65

TRYOUT-DAY STABILITY UPDATE

1. TAKE PHOTO
- Reworked camera button to use explicit DOM references instead of browser-dependent implicit element globals.
- Camera dialog now opens before the permission request.
- Uses a simple video:true request for broader Windows/Chromebook compatibility.
- Camera errors are displayed in the dialog and a startup failure also triggers an alert.
- Upload Photo remains available.

2. FULL BACKUP / RESTORE
- Download Full Backup exports the entire Club Manager state to one JSON file.
- Restore Full Backup imports that file on another computer/browser.
- Includes registrations, check-ins, evaluations, director reviews, placements, teams, offers, parent responses, payment plans, payments, documents, accounting, and settings.
- Available from Workflow Dashboard and Setup.

Existing v0.64 data migrates automatically.
