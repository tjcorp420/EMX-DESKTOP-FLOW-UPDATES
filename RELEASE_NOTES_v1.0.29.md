# EMX Desktop Flow v1.0.29

## Immediate dock restore and minimize toggling

- Fixes the delay required before restoring an app immediately after it was minimized.
- Reads each target window's live visible and minimized state instead of relying only on Windows' briefly stale foreground HWND.
- Serializes rapid clicks for the same dock item so minimize and restore actions cannot race each other.
- Allows the first minimize action a short state-settle interval before evaluating the next click.
- Preserves v1.0.28's launcher, tray-process, hidden-window, frameless-window, and exact TaskBar-pin matching.
- Preserves Control Center power actions and the working Windows sign-in startup behavior.

The installer is covered by `SHA256SUMS.txt` and verified by Desktop Flow before installation. It is not Authenticode signed.
