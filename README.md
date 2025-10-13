# LPD_mask_GUI
Jupyter-based interactive masking utility for LPD1M detector. See screenshot.
![Screenshot](/screenshot.png?raw=true "Screenshot")

Left click to mask, right click to unmask. Select masking unit (chip, tile, module, pixel, column, row) from drop down. Rows and columns are per chip. Red pixels are masked out in the pipeline, magenta pixels are masked manually. You can create a mask per train/pulse or a static mask, identical for every train/pulse.

The transform between data coordinates and real gemoetry is handled by extra_geom snapped geometry.

Requires: <br>
Jupyter <br>
numpy <br>
matplotlib <br>
xarray <br>
IPython <br>
ipywidgets <br>
(from Eu-XFEL) <br>
extra <br>
extra_data <br>
extra_geom

Written by Tobias Eklund and Yizhi Liu (2025) for FXE beamtimes 3273, 7944.
