# Modifications

This repository is a modified version of new-api (https://github.com/QuantumNous/new-api), Copyright (c) QuantumNous and contributors, licensed under the GNU Affero General Public License v3.0 with the additional terms in [NOTICE](NOTICE).

As required by AGPLv3 section 7(c), the changes made in this fork are listed below. The backend (Go code) is unchanged.

| File | Change | First released in |
|---|---|---|
| `web/src/styles/brand.css` | New file: brand colors for the default theme preset (light and dark) | `v1.0.0-rc.51-brand.1` |
| `web/src/styles/index.css` | One line that imports `brand.css` after the theme presets | `v1.0.0-rc.51-brand.1` |
| `MODIFICATIONS.md` | This file | `v1.0.0-rc.51-brand.1` |

The attribution required by NOTICE is kept unchanged: "Frontend design and development by New API contributors." and the link to the original project.

The source of each published image is the git tag of the same name in this repository: `<upstream version>-brand.<n>`.
