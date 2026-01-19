## 0.0.9

### Added

- Add Cursor agent support, including shared memory doc grouping for AGENTS.md.
- Add agent metadata fields (memory group, config hints, capabilities) across core/app/CLI.
- Add grouped memory doc replacement UI and agent picker improvements.
- Add UI navigation smoke test and typecheck to the test pipeline.

### Changed

- Improve onboarding agent detection messaging for agents without history parsers.
- Expand docs with a dedicated add-agent quick guide.

### Fixed

- Prevent shared-memory agents from being locked into replacement selections.

## 0.0.8

### Fixed

- Remove AppleDouble entries from updater tarballs to avoid unpack failures on macOS.

### Changed

- Add a custom background image to the DMG installer window.

## 0.0.7

### Changed

- Versioned release artifact filenames with platform suffix (e.g. `OhMyAgents_0.0.7_macos-arm64.*`) for stable updater URLs.

## 0.0.6

### Added

- Show app version and build number in Settings > About.

### Changed

- Separate dev and release app data directories (dev uses `.dev` suffix).
- Default app data cleanup targets dev directories; use `./scripts/app-clean.sh --release` for production.
- Normalize release artifact filenames (no spaces) to avoid GitHub asset renaming issues.
- Removed the "Active" badge from Settings > Agents.

## 0.0.5

### Changed

- Removed the "Active" badge from agent cells in Settings > Agents.

## 0.0.4

### Fixed

- Fixed in-app auto update not working due to parameter naming mismatch.

## 0.0.3

### Added

- DMG installer now includes Applications folder shortcut for easier drag-to-install experience.

## 0.0.2

### Added

- Auto upgrade support. Now OMA can upgrade itself in-app.
