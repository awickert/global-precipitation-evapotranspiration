# global-precipitation-evapotranspiration
Global 0.25-degree grids of mean precipitation and evapotranspiration from 2000-2004

These grids were created to generate a full modern distributed precipitation and evapotranspiration data product to predict river discharges. These discharges should be equal to P - ET, whether accumulated over the landscape or summed across defined drainage basins, assuming that net groundwater fluxes (in and out) are near 0.

I created these because no such product existed, and I needed it for my paper, "Reconstruction of North American drainage basins and river discharge since the Last Glacial Maximum". This paper includes a description of the data sets that were used to construct these grids, including complete references. A short and unreference list is provided here as a quick guide:

## Precipitation
*  CRU TS3.21 0.5-degree product: continents except Antarctica
*  HOAPS-3 0.25-degree product: ocean except near Antarctica
*  Interpolation between <2-degree gaps between CRU and HOAPS data sets
*  CMAP reanalysis at 2.5-degree resolution: Antarctic region, continent and ocean

## Evapotranspiration
*  MODIS MOD16 30-arcsecond data products: Evapotranspiration for continents except Greenland and Antarctica
*  HOAPS-3 0.25-degree product: Evaporation across all oceans
*  TraCE-21K CCSM3 model outputs, 0 ka time step, 3.5-degree resolution: Evapotranspiration across Greenland and Antarctica
*  Negative evapotranspiration rates were small and likely a result of the interpolation and smoothing scheme; these were set to 0.

Coarse data were spherically interpolated to 0.25 degree resolution. Fine data were upsampled by averaging.

So -- if you need a global precipitation minus evapotranspiration grid for your work, you can get it here! Just please cite:
Reconstruction of North American drainage basins and river discharge since the Last Glacial Maximum: http://www.earth-surf-dynam-discuss.net/esurf-2016-8/,
or the upcoming full paper.
