# EMX Desktop Flow v1.0.23

## Desktop polish, cursor choice, saved color, and temperature repair

- Restores the packaged LibreHardwareMonitor sensor host so supported CPU and GPU temperature readings work again on installed copies.
- Adds a persistent Celsius/Fahrenheit selector shared by the Home dashboard and desktop temperature widget.
- Adds **Keep Current Settings** to Color Studio so users can save the active color setup without creating a named profile; the saved setup is restored at app startup.
- Removes the duplicate page-render pass that made Taskbar, Start, Explorer, and Menu pages flash when opened.
- Consolidates Windows Start, Explorer, and Menu settings under **Windows Shell**.
- Promotes the existing real system audio mixer to **Quick Controls** and adds **Capture Lab** for local screenshot, copy, save, and OCR workflows.
- Renames Taskbar to **Dock & Taskbar** to reflect its full native-taskbar and EMX Dock controls.
- Lets users expand every installed cursor pack, preview each pointer, and apply one pointer individually instead of only applying the complete pack.
- Keeps managed cursor pointers in the Cursor Test Zone after catalog updates.
- Repairs the official background feed by publishing the nine media files that were listed in the catalog but absent from the content release.
- Preserves constrained background-card titles and media previews from v1.0.22.

The installer is covered by `SHA256SUMS.txt` and verified by Desktop Flow before installation. It is not Authenticode signed.
