# Dennis Township Roads at Risk

Static GitHub Pages app for drawing road and cross-section profiles through the Dennis Township municipal DEM.

The interface follows the North Wildwood Roads at Risk reference: threshold presets, NAVD88/MLLW conversion, terrain and hillshade views, saved multi-line cross sections, flood-history and future-frequency charts, and CSV/Shapefile exports.

Municipal constants:

- Observations: USGS 01411435, South Dennis
- PETSS / NOAA station: est0008
- NAVD88 thresholds: 3.55 ft minor, 4.55 ft moderate, 5.55 ft major
- MLLW thresholds: 7.1 ft minor, 8.1 ft moderate, 9.1 ft major
- MLLW = NAVD88 + 3.55 ft

Terrain source: USGS 3DEP Bare Earth DEM Dynamic ImageServer, clipped to the Dennis Township boundary at 18.6-foot adaptive resolution.
