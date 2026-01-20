## 0.0.11

### Added

- Add OpenCode agent support (skills + memory docs), including history-based discovery and icon.
- Add pinned agents in Settings with a 5-agent limit to control which agents appear in pickers.

### Changed

- Show pinned agents in asset agent popovers, with a “More agents…” action to open the full picker.
- Cap inline agent chips in project asset rows and show a +N indicator when more are linked.
- Open the Asset Library when an empty project agent row is clicked, and preselect the clicked agent.
- Soften the core actions guide overlay with stronger blur and slower intro timing.
- Publish a stable DMG filename for website downloads (version shown in the asset label instead).
- Refresh the Antigravity icon.

### Fixed

- Prevent drag-and-drop unlisten errors when opening the Assets view.

## 0.0.10

Rules assets are here, with Antigravity support and flexible memory doc locations across scopes.

### Added

- Add Rules assets so rule files can be distributed alongside skills and memory docs.
- Add Antigravity agent support, including rules + memory doc handling and icon.
- Add Settings > Importing actions to rerun onboarding and rescan all projects.
- Add a feedback entry under the sidebar Help menu.

### Changed

- Allow agent memory doc base paths to differ between user and project scope.
- Update project/asset UI to surface Rules assets and memory doc grouping.
- Adjust onboarding re-entry to skip the welcome step and final guide.
- Show added-or-updated asset counts after a full rescan.

### Fixed

- Clear stale project search filters when navigating away from the Projects page.

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
