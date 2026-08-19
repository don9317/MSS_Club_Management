MSS Club Management Suite Demo v0.53 — Paper Entry / Director Review Repair

FIXED — PAPER SCORE ENTRY
- Restored the correct Paper Score Entry player-list renderer and its actual field IDs.
- Checked-in players now appear again by grade/status/evaluator.
- Existing paper evaluations display rating, recommendation, evaluator and entered-by.
- Enter/Edit Scores opens the lower evaluation form.
- Paper evaluations continue using the established per-player/per-evaluator data structure.

FIXED — DIRECTOR REVIEW
- Director Review again reads the same nested evaluation data used by Coach Quick Form and Paper Score Entry.
- Paper ratings and recommendations flow to Director Review.
- Reviewed By, Review Date, Draft / Reviewed status and Edit Review use the established director-review fields.
- Edit Review reopens a Reviewed record as Draft and makes it editable.
- Old phantom Reviewed statuses with no reviewer are normalized to Draft/Not Reviewed.

ATTENDANCE
- All registered players remain visible to the Director.
- Non-attendees are highlighted and normal Director fields are locked.
- Correct Attendance marks a missed check-in as attended.
- Director Override deliberately unlocks review without changing attendance.

Existing v0.52 browser data migrates automatically.
