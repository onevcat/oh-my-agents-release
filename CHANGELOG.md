## 0.1.3

OMA now supports oma:// deep links and github.com/skills.sh imports for faster sharing and onboarding.

### Added

- Support oma:// deep links to open OMA and start asset imports from supported URLs.
- Accept skills.sh URLs (with skill filters) and highlight filtered skills in the import picker.
- Add a Settings toggle to control whether OMA links ask for confirmation or auto-import.

### Changed

- After importing assets, guide you to choose a project and agents before finishing the link.
- Refine the OMA link confirmation dialog layout and inline import progress feedback.

## 0.1.2

### Added

- Add Droid/Factory agent support (skills + memory docs), including history-based discovery and icon.

### Changed

- Improve agents row to support horizontal scrolling with drag-to-scroll for mouse users.
- Refine global scrollbar styling: thinner track and lighter colors for both light and dark modes.

### Fixed

- Fix User Scope memory doc linking so memory docs can be properly reused across agents.
- Show replace dialog when enabling an agent would cause a memory doc conflict.

## 0.1.1

### Fixed

- Fix unlinking rules with "Delete synced files" so Antigravity files stored under `.agent/rules` are removed correctly.

## 0.1.0

Beta starts here, with Amp support and smarter onboarding imports.

### Added

- Add Amp agent support (skills + memory docs), including history-based discovery and icon.

### Changed

- Make onboarding import previews and rule creation respect the agents you selected, and link AGENTS.md to every enabled agent that supports it.
- Default agent selection now follows pinned agents; onboarding auto-pins selected agents (up to 5) and defaults to Claude + Codex.

## 0.0.11

### Added

- Add OpenCode agent support (skills + memory docs), including history-based discovery and icon.
- Add pinned agents in Settings with a 5-agent limit to control which agents appear in pickers.

### Changed

- Show pinned agents in asset agent popovers, with a "More agents…" action to open the full picker.
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

## 0.0.6

### Added

- Show app version and build number in Settings > About.

### Changed

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
