MSS Club Management v0.81 — Storage Architecture

WHY THIS VERSION EXISTS
v0.80 exposed the browser localStorage quota limit. Earlier development builds could retain separate full data copies under version-specific keys (v0.68-v0.80), which eventually consumed the small localStorage allowance.

WHAT CHANGED
- Club data now uses one permanent IndexedDB database: MSSClubManagement.
- App releases no longer create a new full browser-data copy for each version.
- On first v0.81 launch, the app looks for the newest existing v0.68-v0.80 localStorage data if no v0.81 database exists.
- Existing data is loaded and written to the new database first.
- Only after that database write succeeds are obsolete version-specific localStorage copies removed.
- If migration cannot be completed, the old data is left in place and the app warns the user to make a backup.
- No demo players load automatically. The 150-player demo remains optional.
- v0.80 native MSS registration CSV import support is retained.
- Backup/Restore now writes restored data to the permanent database rather than a version-specific localStorage key.

IMPORTANT
On the first launch after deploying v0.81, use the same browser/profile/device that contains the existing MSS prototype data so v0.81 can migrate it. After confirming the data is present, use Backup Club Data to create a JSON backup.

PRODUCTION NOTE
IndexedDB is appropriate for this browser prototype and provides substantially more capacity than localStorage. A production multi-user MSS system should ultimately store authoritative club data and photos server-side/cloud-side rather than only in one browser.
