MSS Club Management Suite Demo v0.48 — Registration Load Repair

FIXED
- Restored the missing Master Registration List renderer.
- Generate 150 Demo Players now visibly loads and confirms success.
- CSV Import now visibly confirms file read/import success.
- Included Demo CSV handles UTF-8 BOM correctly.
- CSV parser supports quoted values.
- Clear All restored.
- renderAll is now resilient: a missing optional renderer cannot stop the rest of the application.
- Added a visible Registration Data status message so users can see whether data loaded or failed.
- Existing v0.47 browser data migrates automatically.
