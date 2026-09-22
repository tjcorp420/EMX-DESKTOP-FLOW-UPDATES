# EMX Desktop Flow v1.0.31

## Visual Audio availability, route isolation, and wallpaper favorites

- Includes the complete EMX Visual Audio 0.6 companion in every Desktop Flow installer so clean PCs no longer report that it is missing.
- Adds an in-app **Install Visual Audio** state that creates the standalone Windows app shortcut and then launches the included companion.
- Detects an existing Visual Audio installation and shows **Launch Visual Audio** instead of reinstalling it.
- Keeps the embedded Visualizer window hidden after restoring Desktop Flow unless the Visualizer route is actually active.
- Prevents the Visualizer surface from appearing above Settings, Wallpaper, or other tabs after minimizing and restoring the app.
- Normalizes wallpaper favorite identifiers, validates them against the live library, and uses a larger accessible favorite button with success and failure feedback.

The installer is covered by `SHA256SUMS.txt` and verified by Desktop Flow before installation. It is not Authenticode signed.
