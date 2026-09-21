# EMX Desktop Flow v1.0.20

This release stabilizes the live-wallpaper and Visual Audio desktop pipelines and completes the custom Layer Studio bar workflow.

## Fixed

- Live wallpapers now attach to the Windows desktop layer behind icons and the taskbar.
- Wallpaper sizing now follows the active display instead of leaving black regions or cropping into one corner.
- Visual Audio Desktop Mode now uses the same reliable desktop-host path.
- Custom Layer Studio bars no longer animate without demo audio or a real audio signal.
- Custom bar scenes now use square rectangular columns, denser spacing, improved bass/beat response, and the same Sensitivity, Smoothing, Glow, Detail, Beat Pulse, scale, and count controls as built-in scenes.
- Visualizer navigation no longer leaks clicks into unrelated Desktop Flow tabs.

## Added

- Layer Studio can choose an animated background already imported into Desktop Flow or select a GIF, MP4, WebM, or image from disk.
- The bundled Visual Audio companion includes the same Layer Studio and desktop-mode fixes as the integrated experience.

## Update safety

- The installer remains unsigned and may show Windows SmartScreen's Unknown Publisher warning.
- Desktop Flow downloads this installer only after its SHA-256 digest matches `SHA256SUMS.txt` from this release.
