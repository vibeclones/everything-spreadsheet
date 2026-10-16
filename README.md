# everything-spreadsheet (Vibeclones mirror)

Hosted builds of the **spreadsheet** app from Puter's [Everything](https://github.com/HeyPuter/everything) project (MIT). The code is theirs; this repo only builds and hosts it.

- Latest: `/everything-spreadsheet/latest/`
- A specific snapshot: `/everything-spreadsheet/v<snapshot>/`
- Snapshot list: `/everything-spreadsheet/versions.json`

Upstream doesn't publish releases or version numbers yet, so each snapshot is named after the date and short hash of the last upstream commit that touched `src/spreadsheet`, for example `v2026.10.16-ab12cd3`. These are not official releases. A scheduled workflow builds a new snapshot when that app changes upstream.