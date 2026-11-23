# Modifications

This repository is untoken, a modified version of new-api (https://github.com/QuantumNous/new-api), Copyright (c) QuantumNous and contributors, licensed under the GNU Affero General Public License v3.0 with the additional terms in [NOTICE](NOTICE).

As required by AGPLv3 section 7(c), the changes made in this fork are listed below. The backend (Go code) is unchanged.

| File | Change | Since |
|---|---|---|
| `web/src/styles/brand.css` | New file: untoken colors and corner radius for the default theme preset (light and dark), the untoken typefaces for the Auto font choice and for monospace text, the layout and type of the public pages' header, the site name in the console's top bar, and the look of the logo, the sign-in pages, Model Square and About (styles only) | `v1.0.0-rc.51-brand.1`; colors changed in `v1.0.0-rc.51-brand.2`; radius, typefaces and page styles added in `v1.0.0-rc.51-brand.3` |
| `web/src/styles/brand-fonts/` | New files: the Geist and Geist Mono fonts by Vercel, unmodified, with their license (`OFL.txt`, SIL Open Font License 1.1) | `v1.0.0-rc.51-brand.3` |
| `web/src/styles/index.css` | One line that imports `brand.css` after the theme presets | `v1.0.0-rc.51-brand.1` |
| `web/public/brand/untoken-mark.svg` | New file: the untoken logo, which the site settings can point to | `v1.0.0-rc.51-brand.2` |
| `MODIFICATIONS.md` | This file | `v1.0.0-rc.51-brand.1` |
| `.github/workflows/brand-sync.yml` | New file: moves the brand commits onto each upstream release, then builds, tests and publishes the image. The workflows inherited from upstream are kept unchanged but disabled in this repository | `v1.0.0-rc.51-brand.1` |

The attribution required by NOTICE is kept unchanged: "Frontend design and development by New API contributors." and the link to the original project. The new-api logo and name in the source are unchanged; the untoken name and logo are shown through the site settings.

The source of each published image is the git tag of the same name in this repository: `<upstream version>-brand.<n>`.
