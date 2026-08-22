v0.71 — Program-to-Grade Import Repair

- Grade is again pre-populated from the registration CSV and remains editable.
- Program header detection is now flexible: any header containing the word "Program" is accepted.
- Program text recognizes:
  3rd / 4th / 5th etc.
  3rd Grade / 4th Grade
  Grade 3 / Grade: 3
  Third Grade / Fourth Grade
  labels containing one standalone grade number.
- Raw Program is still displayed in the Registration table for verification.
- Import confirmation reports the exact Program column header it found and how many grades were recognized.
- Existing v0.70 live browser data migrates forward.
