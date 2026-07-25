# ERA-5 Gridded Climate Data Visualization

Exploratory analysis and visualization of ERA-5 reanalysis climate data (temperature, humidity, wind) 
using xarray and matplotlib — covering grid interpolation methods, scatterplot matrices, and 
multi-variable visualization techniques (brushing & linking).

## What's covered
- **Grid analysis**: inspecting ERA-5 grid characteristics, spacing, and coordinate systems using xarray
- **Interpolation**: comparing nearest-neighbour, bi-linear, and bi-cubic interpolation for gridded temperature data
- **Scatterplot matrices**: visualizing relationships between temperature, humidity, and wind across regions
- **Multi-channel encoding**: mapping pressure level to marker size/color across visualizations
- **Regional comparisons**: Germany vs. North Atlantic, Northern vs. Southern Hemisphere patterns

## Data
Uses ERA-5 hourly reanalysis data (not included — large file size + licensing). 
Download from the [Copernicus Climate Data Store](https://cds.climate.copernicus.eu/) 
for the relevant date/region to reproduce.

## Tech stack
`Python` `xarray` `NumPy` `Matplotlib` `netCDF4`
