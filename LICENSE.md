# Licences of the outputs in this folder

Applied 2026-10-31 as recommended in `docs/LICENSING_ANALYSIS.md` of the flood-schools repository (owner-confirmed).
Not legal advice. The code that made these files is MIT; the files themselves keep the terms of their sources.

| Output | Licence | Notes |
|---|---|---|
| `schools_exposure_public.gpkg` | ODbL 1.0 (https://opendatacommons.org/licenses/odbl/1-0/) | Public school database: OSM schools, COD-AB admin fields, TU Wien flags. No per-school UNOSAT columns |
| `flood_schools_map_public.html` | ODbL 1.0 for the school points; CC BY-SA 4.0 for the flood-extent and district layers | No per-school UNOSAT styling |
| `schools_exposure.gpkg`, `flood_schools_map.html` | **Internal, not for public release** | Hold per-school UNOSAT flags (CC BY-SA) in an OSM derivative database (ODbL); the two licences are incompatible. Release only after written permission from UNITAR-UNOSAT |
| `maps/*.png` | CC BY-SA 4.0 (https://creativecommons.org/licenses/by-sa/4.0/) | OSM Produced Works; credit line printed on each map |
| `tables/*` | CC BY-SA 4.0 | See `tables/README.md` for the ODbL 4.3 notice and credits |
| `METHODS_NOTE.md` (text) | CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/), text © 2026 Syed Hasnain Akber | Tables and maps quoted in it keep their own licences |
| `nightlights_status.md` | Shareable with attribution | NASA VIIRS Black Marble VNP46A4 (NASA open data; cite the product) |
| `recovery/*` | See `recovery/README.md` | Files with Relative Wealth Index values are non-commercial (CC BY-NC 4.0) |

## Credits

- © OpenStreetMap contributors (ODbL 1.0), via Geofabrik and HOT
- UNOSAT / UNITAR flood extents FL20220808PAK and FL20250818PAK (CC BY-SA)
- TU Wien Sentinel-1 flood frequency 2022, doi:10.48436/zvvmh-nan78 (CC BY 4.0)
- WorldPop R2025A, University of Southampton (CC BY 4.0)
- OCHA COD-AB Pakistan / WFP (CC BY 3.0 IGO)
- Contains modified Copernicus Sentinel data [2021-2025]
- ESA WorldCover (CC BY 4.0); Copernicus DEM
- NASA VIIRS Black Marble VNP46A4
- Relative Wealth Index, Chi et al. 2022, PNAS (CC BY-NC 4.0)

## OpenStreetMap notice (ODbL 4.3)

Contains information from OpenStreetMap (© OpenStreetMap contributors), which is made available under the Open Database License (ODbL) 1.0, https://opendatacommons.org/licenses/odbl/1-0/. The derived school database and the method used to make it are available under ODbL: Method and code: the flood-schools repository (MIT), see README.md and DATA_SOURCES.md.

Boundaries are OCHA COD-AB as published; they are not authoritative and imply no position on disputed territories.
Exposure is not damage.
