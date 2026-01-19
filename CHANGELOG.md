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

### Removed

- Removed the "Active" badge from Settings > Agents.

## 0.0.5

### Changed

- Removed the "Active" badge from agent cells in Settings > Agents.

## 0.0.4

### Fixed

- Fixed in-app auto update not working due to parameter naming mismatch.

## 0.0.3

### Improved

- DMG installer now includes Applications folder shortcut for easier drag-to-install experience.

## 0.0.2

### Added

- Auto upgrade support. Now OMA can upgrade itself in-app.
