# Week 4<br>More Interactive Data Viz, Working with Raster Data

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MUSA-620-Fall-2019/week-4/master?filepath=lecture-4.ipynb)

## Updating your local environment

First, download the `environment.yml` file in this repository to your computer.

**Important**: if you are on a Windows machine, make sure that `.txt` wasn't appended to the file name when you downloaded it. If so, you will need to rename it so the file ends in `.yml`.

Then you can run, from either the Anaconda Prompt (Windows) or Terminal app (MacOS):

```
conda env update --file environment.yml --name musa-620
```

where `musa` should be the name of the environment you have been using.

Then you can activate the environment and start a notebook

```
conda activate musa-620
```

## Topics

- hvplot, Holoviews, GeoViews
- Raster data
- rasterio, xarray

## Readings

- [hvplot User Guide](https://hvplot.pyviz.org/user_guide/index.html)
- [Rasterio Quickstart](https://rasterio.readthedocs.io/en/latest/quickstart.html)

## References

- [HoloViz tutorial](https://holoviz.org/talks/index.html): introduction to the HoloViz ecosystem
- [HoloViews user guide](http://holoviews.org/user_guide/index.html) and [gallery](http://holoviews.org/gallery/index.html)
- [GeoViews user guide](http://geoviews.org/user_guide/index.html) and [gallery](http://geoviews.org/gallery/index.html)
- [Rasterio documentation](https://rasterio.readthedocs.io/en/latest/index.html)
- [More info on CRS](https://datacarpentry.org/organization-geospatial/03-crs/index.html)
- [EarthPy examples gallery](https://earthpy.readthedocs.io/en/latest/gallery_vignettes/index.html)
- [Plotting with rasterio](https://rasterio.readthedocs.io/en/stable/topics/plotting.html)
- [LandSat bands](https://www.usgs.gov/faqs/what-are-best-landsat-spectral-bands-use-my-research?qt-news_science_products=0#qt-news_science_products)
- [Tutorial on Landsat data](https://www.earthdatascience.org/courses/earth-analytics-python/multispectral-remote-sensing-in-python/landsat-bands-geotif-in-Python/)
- [Xarray overview](http://xarray.pydata.org/en/stable/quick-overview.html)
