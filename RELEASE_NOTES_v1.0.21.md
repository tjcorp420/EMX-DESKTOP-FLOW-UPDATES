# EMX Desktop Flow v1.0.21

This update expands the background-pack pipeline for large animated wallpaper files while preserving the wallpaper and Visual Audio fixes delivered in v1.0.20.

## Added

- Background packs now accept `.mov` animated wallpapers in both the private owner publisher and the customer catalog installer.
- The maximum supported individual background asset is now 1 GB.

## Improved

- Large background assets are hashed as streams in the owner tool instead of loading the entire file into memory.
- Customer background downloads are streamed directly to disk and verified with SHA-256 before installation.
- Failed, oversized, or hash-mismatched downloads are cleaned up instead of being installed.

## Verified

- The supplied 757.4 MiB H.264 MOV background passes the real owner-tool inspection path.
- Content-catalog tests cover MOV acceptance and continue to protect allowed download hosts and catalog validation.

## Update safety

- The installer remains unsigned and may show Windows SmartScreen's Unknown Publisher warning.
- Desktop Flow accepts catalog media only from approved HTTPS GitHub hosts and verifies the published SHA-256 digest before installation.
