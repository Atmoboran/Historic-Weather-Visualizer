# Weather Visualization and Animation Notebook

This project automates the visualization and animation of weather data using NOAA datasets. The notebook allows users to download weather data, process it, and create animated visualizations for various weather variables like temperature, humidity, and more.

## Features

- **Data Download**: Automates the download of weather datasets from NOAA.
- **Weather Variables Supported**:
  - Temperature
  - Relative Humidity
  - Wind
  - Rain
  - Low and High Clouds
  - Snow
- **Custom Visualization**:
  - Adjustable latitude/longitude ranges.
  - Multiple color palettes for plots.
  - Option to overlay world maps.
- **Animation**:
  - Generates time-series animations for the selected variable.
  - Option to save animations as MP4 files.

## Requirements

To run this project, you need the following Python libraries installed:

- `cartopy`
- `xarray`
- `matplotlib`
- `numpy`
- `requests`
- `IPython`
- `urllib`

You also need `ffmpeg` installed for saving animations as MP4 files:
```bash
# On Ubuntu/Debian
sudo apt install ffmpeg

# On MacOS using Homebrew
brew install ffmpeg
