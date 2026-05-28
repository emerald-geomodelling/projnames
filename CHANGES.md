# Changelog

## 0.0.3

### Changed
- Migrate off `pkg_resources` (removed in setuptools 81) to `importlib.resources`
  for loading the bundled `epsgnames.json`, and close the resource handle after load.

No other functional changes since 0.0.2.
