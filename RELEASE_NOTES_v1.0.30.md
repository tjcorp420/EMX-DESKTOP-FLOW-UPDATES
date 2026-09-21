# EMX Desktop Flow v1.0.30

## Faster, deterministic Windows sign-in startup

- Moves Desktop Flow from Explorer's delayed Run-key queue to a limited per-user logon task, with the existing login-item path retained as an automatic fallback.
- Skips the splash window during hidden sign-in startup so it never steals focus or delays the desktop.
- Restores taskbar styling, animated wallpaper, Visual Audio desktop mode, and EMX Dock before nonessential cursor, widget, motion, and effects services.
- Reasserts desktop surfaces while Explorer and WorkerW settle after sign-in.
- Defers the hidden control panel, catalog checks, and startup-registration repair until critical desktop surfaces are ready.
- Adds a bounded `startup-timeline.log` in the app data folder for evidence-based startup diagnosis.

The installer is covered by `SHA256SUMS.txt` and verified by Desktop Flow before installation. It is not Authenticode signed.
