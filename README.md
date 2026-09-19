# EMX Desktop Flow Updates

Official release feed for EMX Desktop Flow.

The application checks this repository's latest GitHub Release. Every Windows installer is published with `SHA256SUMS.txt`; EMX refuses to install a download that does not match its published SHA-256 digest.

## Release assets

- `EMX Desktop Flow Setup <version>.exe` — Windows NSIS installer.
- `SHA256SUMS.txt` — required integrity manifest.

Updates are never installed silently. Users explicitly check, download, verify, and start installation from EMX Settings.
