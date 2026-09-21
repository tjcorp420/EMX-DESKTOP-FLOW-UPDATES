# EMX Desktop Flow v1.0.26

## Per-device backgrounds, login restoration, and dock behavior

- Background drops are discovered automatically but no longer download silently. Each computer now requires an explicit Download choice.
- Already-downloaded catalog cards provide a working **View in My Backgrounds** action and refresh the local wallpaper library before opening it.
- Launch-at-login registration is repaired against the current installed executable on startup, including after an app update changes its path.
- Wallpaper and dock restoration retries after Explorer and the desktop host settle at login instead of failing permanently when Windows starts EMX too early.
- Wallpaper reattachment is now verified; an unattached surface is rebuilt instead of being treated as active.
- Dock clicks use a fresh live-window snapshot and the current foreground window: click to restore/focus, then click again to minimize.
- Dock minimization now uses a verified native minimize operation with a message fallback.
- Windows pinned-app discovery now scans nested TaskBar and ImplicitAppShortcuts folders, recovering Steam and other pins missed by the previous top-level-only scan.

The installer is covered by `SHA256SUMS.txt` and verified by Desktop Flow before installation. It is not Authenticode signed.
