# EMX Desktop Flow v1.0.28

## Correct running-state detection and real dock window toggling

- Fixes running apps being treated as closed when a taskbar shortcut points to a launcher, updater, or tray executable.
- Adds launcher-aware matching for applications such as Discord and Logitech G HUB.
- Tracks tray-only pinned applications as running without adding unrelated processes or shortcuts to the dock.
- Finds nonstandard hidden application windows by their already-matched process ID, allowing apps such as EMX VOLT MACRO and Logitech G HUB to restore from the dock.
- Supports frameless taskbar applications whose native window title is empty.
- Keeps the last genuine foreground application while the pointer moves onto the transparent dock, enabling click-again-to-minimize behavior.
- Preserves v1.0.27's exact TaskBar-only pin source, Control Center power actions, and working Windows sign-in startup restoration.

The installer is covered by `SHA256SUMS.txt` and verified by Desktop Flow before installation. It is not Authenticode signed.
