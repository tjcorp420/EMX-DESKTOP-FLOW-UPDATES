# EMX Desktop Flow v1.0.27

## Exact taskbar mirroring, reliable dock toggling, and PC power controls

- EMX Dock now reads only Windows' real TaskBar pinned-shortcut folder. Start-menu and implicit shortcut artifacts no longer appear as extra dock items.
- Running, unpinned taskbar apps still appear while they are open, matching normal Windows taskbar behavior.
- Dock clicks now verify which app actually reached the foreground and retry restoration once when Windows delays the first focus request.
- Clicking the visible app again minimizes its real top-level window, including when the transparent dock temporarily obscures foreground detection.
- EMX Control Center now includes Lock, Sleep, Restart, and Shut down actions.
- Every PC power action requires an explicit confirmation inside Control Center before Windows receives the command.
- The working launch-at-Windows-sign-in restoration from v1.0.26 is unchanged.

The installer is covered by `SHA256SUMS.txt` and verified by Desktop Flow before installation. It is not Authenticode signed.
