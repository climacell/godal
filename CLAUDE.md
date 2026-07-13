# godal

Go bindings for GDAL. Fork of [airbusgeo/godal](https://github.com/airbusgeo/godal).

## GDAL version support

- **v1.0.5+**: requires GDAL >= 3.11. The VSI virtual filesystem API changed in GDAL 3.11 (`Open()` returns `unique_ptr`, `Read()`/`Write()` use single `nBytes` param, `InstallHandler()` takes `shared_ptr`).
- **v1.0.4 and earlier**: supports GDAL 3.7–3.10.
