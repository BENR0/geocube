History
=======

Latest
------

0.1.1
-------
- DEP: Drop Python 3.7 Support (issue #86)
- BUG: Updated logic to skip rasterizing strings for numpy 1.22+ (issue #88)

0.1.0
------
- ENH: Minimize dtype when possible in `geocube.rasterize.rasterize_image` (issue #72)
- REF: remove unnecessary shapely.geometry.mapping in rasterize_image (#80)
- ENH: `vector_data` to read path-like objects (pull #81)

0.0.18
------
- DEP: Explicitly add scipy as dependency (pull #75)

0.0.17
------
- DEP: Python 3.7+ (#67)
- REF: Write grid_mapping to encoding instead of attrs (#66)

0.0.16
------
- BUG: Compatibility with rioxarray 0.3 (#57)

0.0.15
------
- Address xarray & numpy deprecations (#43)

0.0.14
------
- Add "all_touched" keyword argument to geocube.rasterize.rasterize_image (pull #40)

0.0.13
------
- Address deprecation warnings from datacube and rioxarray (issue #29)

0.0.12
------
- ENH: Added :func:`geocube.show_versions` and cli `geocube --show-versions` (pull #23)
- Add compatibility between datacube and geopandas CRS versions (pull #24)

0.0.11
------
- Drop Python 3.5 Support (issue #12)
- ENH: Update to support geopandas with pyproj.CRS (pull #18)
- BUG: Update timestamp handling to ensure correct format for dtype (pull #18)

0.0.10
------
- Added filter_nan kwarg to filter out missing data when rasterizing (issue #9)
- Change default fill value to NaN when rasterizing (pull #11)

0.0.9
-----
- Added `rescale` kwarg to `geocube.rasterize.rasterize_points_griddata`. (pull #8)
- Removed `fillna(numpy.nan)` in `geocube.geo_utils.geobox.load_vector_data` as not necessary
  and for compatibility with `geopandas==0.6.0`. (pull #8)

0.0.8
-----
- Add merge algorithm option for rasterization (issue #5)
- Drop Python 2 support (issue #6)

0.0.7
-----
- Remove geocube pin (pull #4)

0.0.6
-----
- Added additional methods for resampling points to a 2D grid (pull #3)

0.0.5
-----
- Fix converting to another projection to ensure bounds are correctly accounted for (pull #2)
