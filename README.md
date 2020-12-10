# rces-final-project
For my final RCES project, I analyzed the weather and climate anomalies that contributed to the record-breaking 2018 wildfire season in the North American West using [ERA-Interim](https://www.ecmwf.int/en/forecasts/datasets/reanalysis-datasets/era-interim) reanalysis data, and correlated atmospheric anomalies with a [burned-area dataset](https://modis.gsfc.nasa.gov/data/dataprod/mod45.php) in California to see whether these atmospheric anomalies from 2018 are typical of high fire seasons.

### Analysis 
I visualized seasonal anomalies in several climatic factors for the year preceding the 2018 fire season, using the monthly climatology of the 1979-2018 period, including precipitation, temperature, vapor pressure deficit, winds at 700mb, vertical velocity at 700mb, and geopotential height at 200 mbar. For some of these variables, I standardized the anomalies by dividing by their standard deviations. After describing the large-scale dynamical environment in the year leading up to this extreme fire season, I characterized the burned area data in California over the 1984-2018 period and regressed 200 mbar geopotential height anomalies from winters preceding fire seasons onto the burned area data for the following July. 

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/tessjacobson/rces-final-project/HEAD)
