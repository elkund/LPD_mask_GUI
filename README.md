# LPD_mask_GUI
Jupyter-based interactive masking utility for LPD1M detector. See screenshot.
![Screenshot](/screenshot.png?raw=true "Screenshot")

Left click to mask, right click to unmask. Select masking unit (chip, tile, module) from drop down. Red pixels are masked out in the pipeline, magenta pixels are masked manually. You can create a mask per train/pulse or a static mask, identical for every train/pulse.

The transform between data coordinates and real gemoetry is handled by extra_geom snapped geometry.

Requires:
Jupyter
matplotlib
xarray
IPython
ipywidgets
(from Eu-XFEL)
extra
extra_data
extra_geom

Written by Tobias Eklund and Yizhi Lui (2025) for FXE beamtimes 3273, 7944.
