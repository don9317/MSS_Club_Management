v0.70 — Live Tryout Stability Fix

CSV / GRADE
- Registration CSV now reads grade from the Program field when no Grade field is present.
- Recognizes common forms such as 3rd, 3rd Grade, Grade 3, 4th Girls, etc.
- Registration table now displays the imported Program value for verification.
- Unrecognized grades show Select Grade instead of silently appearing as 3rd grade.

CAMERA
- Camera request is now non-blocking.
- If a camera does not open within 6 seconds, the camera window automatically closes and Check-In remains usable.
- A clear alert tells staff to use Upload Photo instead.
- Close / Skip Camera always cancels the camera attempt and stops any late stream.
- Upload Photo remains available and is the recommended fallback during the live tryout if webcam access is unreliable.

Existing v0.69 live browser data migrates forward.
