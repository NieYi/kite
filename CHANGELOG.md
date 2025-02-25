# Changelog

All notable changes to Kite will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

## [1.2.3] 17. July 2019

### Added
- `Scene` added `__i/add__`, `__i/sub__` and `__neg__` standard operators.
- Talpa dialog to change LOS vectors (phi and theta) of forward modelled scene.

### Fixed
- MacOS gcc install with OpenMP.
- `stamps2kite` Backward compat MATLAB import.
- `covariance`/`quadtree` more defensive against sparsely correlated scenes.
- LiCSAR import more defensive data handling.

## [1.2.2] 26. June 2019

### Added
- scene displacement pixel variance attribute`displacement_px_var`.
- quadtree and covariance propagation of `displacement_px_var` towards diagonal.
- spool to display `displacement_px_var`.
- More meta information for `stamps2kite`.

### Fixed
- `stamps2kite`: look angle import

## [1.2.1] 17. June 2019

### Fixed
- `stamps2kite` import of look angle is now from interpolation.

## [1.2.0] 14. June 2019

### Added
- `stamps2kite` conversion tool.

### Fixed
- ISCE import: XML tag cases.
- Version numbering in `setup.py`

## [1.1.1] 6. June 2019

### Added
- Deramping of displacement maps `Scene.displacement_deramp()`

### Fixed
- Spool more digits for degree scenes
- Fixed log handling and handler injection

## [1.1.0] 6. May 2019

### Added
- Added LiCSAR import
- Added SARSCAPE import
- Added LiCSAR downloader (`client.py`)
- Added CLVDVolume to talpa
- Added SpinBox for sliders

### Fixed
- talpa various improvements and bugfixes
- updated documentation
- fixed import for ROIPAC and ISCE
- matplotlib plotting functions

### Changed
- Spool: Changes 'LOS' to 'Towards Satellite'

## [1.0.1] 21. January 2019

### Added
- Adapting semating versioning
- Spool: added log control

### Fixed
- Improved log control
- Documentation fixes and internal references.
- Fixed Gamma import from Lat/Lon
- docs: Removed Anaconda pre-build installation
