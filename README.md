# India-Multi-Hazard-Risk-Data-Pipeline-for-Buildings-Infrastructure
# DESCRIPTION
A reproducible mini-pipeline that ingests building footprints + two hazard rasters (rainfall, heat, flood, etc) and outputs per-building exposure scores.
It assigns each building the nearest hazard measurements and computes a normalized exposure score.
the datasets i have used are precipitation(mm) and wind speed at 10m(m/s) from NASA POWER for last 1 year.
the building footprint is of 14000 buildings from very small sybregion of mumbai that is why each building has been assigned with same paramter value, since value of rainfall or windspeed doesnt vary for small region

## Requirements
- Python 3.10+
- geopandas
- pandas
- numpy
- scipy
- scikit-learn
- rasterio (if using TIF raster files)

You can install all dependencies using:

```bash
pip install geopandas pandas numpy scipy scikit-learn rasterio
```





