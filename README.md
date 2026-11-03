# quickbar.pro plugin updates

One JSON file per plugin. Each plugin reads its file and compares `version` with the version it runs.

- `after-effects.json`: quickbar.pro for After Effects
- `premiere-pro.json`: quickbar.pro for Premiere Pro

Fields: `version` (latest), `message` (shown in the popup), `link` (button target), `force_update` (`true` blocks use until updated).
