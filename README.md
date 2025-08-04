[![DOI](https://zenodo.org/badge/1008219657.svg)](https://doi.org/10.5281/zenodo.16739291)
# Super-Resolution of Waterbody with DEM and Hydrodynamics (SRWD-Hydro)
Combined with Digital Elevation Mpdel (DEM), the resolution of water identification results can be improved, and calculate more credible flood risk mapping with water surface elevation and water depth
![screen capture](/PNG_ASSET/Figure.png)


# Description
This repository houses the code and data resources for running **SRWD-Hydro v1.0** in Jupyter environments. 
**Key Features of Vision 1.0:**
*   **Minimal Input Requirements:** Only requires target terrain data and a coarse-resolution water body identification mask.
*   **Computational Efficiency:** Delivers results with significantly fast processing times.
*   **Enhanced Geographic Fidelity:** Generates outputs with superior preservation of geographic features versus mathematical interpolation approaches.
*   For more detailed parameter settings and their meanings, please refer to the code and literature.


## Dependencies

This project requires the following Python (3.11) libraries:

### Core Geospatial & Image Processing
- **rasterio** (>=1.3.6)
- **opencv-python** (cv2) (>=4.9.0)
- **scikit-image** (skimage) (>=0.22.0)

### Scientific Computing & Mathematics
- **numpy** (>=1.26.4)
- **scipy** (>=1.12.0): 
- **astropy** (>=5.3.4)

### Visualization & Plotting
- **matplotlib** (>=3.8.0)
- **seaborn** (>=0.12.2)

### Utilities & System Operations
- **tqdm** (>=4.65.0), optional but recommended

#The above version of pip is only the minimum version in experiment, and it is uncertain with the lower version.

## Installation
Install all dependencies via 
//pip install (pip name)//
or download current version pips in https://pypi.org/
