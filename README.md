# SnapPlanet places

Pictures of the hand-picked places of the SnapPlanet iPhone app, made every week from free Sentinel-2
and Landsat imagery and served at https://jjrom.github.io/snapplanet-data/.

- `places/<id>.json`: the place's passes of the last year, its opening picture and, for "Decades" places,
  one clear picture a year since 1984.
- `places/<id>/…`: the pictures.

Contains modified Copernicus Sentinel data (processed by SnapPlanet) and Landsat imagery courtesy of the
U.S. Geological Survey.

The workflow (`.github/workflows/publish.yml`) builds the renderer from SnapPlanet's private repository
and runs `snaptest publish`. Nothing here is needed for the app to work: without these files it makes
the pictures itself.
