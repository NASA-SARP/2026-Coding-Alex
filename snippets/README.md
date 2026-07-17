# snippets

This folder contains general code snippets.

## Stream / download data
* [Download data from an AWS bucket](download_aws_data.ipynb)
* [Download data from NASA EarthData using `earthaccess`](download_earthaccess_data.ipynb)
* [Download data from Copernicus EODC using STAC API](download_copernicus_eodc_data.ipynb)
* [Download data from Google Earth Engine](download_earthengine_data.ipynb)

## Processing / analysis
* [Process spatially aggregated time-series data from Google Earth Engine](process_earthengine_timeseries.ipynb)
* [Process data from NASA EarthData to create a multi-year region-mean time-series](process_earthaccess_data_timeseries.ipynb) _(written by Rachel Wegener and contributed by Shimi Goldberger)_
* [Create an annual cloud-free surface reflectance composite from Google Earth Engine](process_landsat_composite_earthengine.ipynb) _(contributed by Kira Baker)_
* [Stack many image dates into a single data cube using `xarray`](Read_Many_MODIS_Example.ipynb) _(written by Jack Dechow)_
* [Resample swath data to a regular grid using `pyresample`](resample_swath_data_to_grid.ipynb)

## Visualization
* [Create an animated mp4 map plot over multiple dates using `imageio`](create_animated_figure_mp4.ipynb)

## Dataset specific
* [Stream and process SMAP L4 soil moisture data via `earthaccess`](process_smap_earthaccess.ipynb) _(contributed by Taryn Andersen)_
* [Access USGS stream gauge data via `dataretrieval.waterdata`](access_usgs_gauge_data.ipynb) _(contributed by Cree Taylor)_
* [Resample NASA TEMPO swath data to a regular grid using `pyresample`](resample_swath_data_to_grid_TEMPO.ipynb) _(contributed by Marin Stevens)_

