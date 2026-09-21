# EMX Desktop Flow v1.0.25

## Wallpaper stability and Capture Lab

- Animated background thumbnails now load only near the viewport and play only while hovered, preventing large background packs from starting many video decoders at once.
- The official background catalog is rendered only in Library instead of being duplicated inside My Backgrounds, Effects, and Audio Reactive.
- The active desktop wallpaper now performs bounded automatic recovery if its renderer exits unexpectedly instead of remaining black.
- Quick Capture can be started again immediately after cancelling with Escape.
- Capture Lab now includes a private local screenshot library with thumbnails, search, tags, favorites, open, show-in-folder, copy-to-send, and confirmed delete actions.
- Preserves the v1.0.24 background thumbnail refresh fix and all v1.0.23 functionality.

The installer is covered by `SHA256SUMS.txt` and verified by Desktop Flow before installation. It is not Authenticode signed.
