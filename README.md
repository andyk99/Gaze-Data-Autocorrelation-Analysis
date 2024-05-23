# Gaze-Data-Autocorrelation-Analysis

This project contains an analysis of eye-movement data recorded during virtual reality video game play. The analysis is aimed at understanding the effect of time on gaze stability, measured by fluctuations in gaze points (X, Y, Z coordinates) across different VR games. The project includes both the R Markdown file used for the analysis and the generated PDF report.

## Files

- `GazeData_TimeSeries_Analysis.Rmd`: The R Markdown file containing the code and analysis.
- `GazeData_TimeSeries_Analysis.pdf`: The PDF report generated from the R Markdown file.
- `BeatSaber_11-12-2020_GazeDataAll.txt`: The text file containing BeatSaber Gaze Data.
- `PistolWhip_11-12-2020_GazeDataAll.txt`: The text file containing PistolWhip Gaze Data. 

## Description

The `GazeData_TimeSeries_Analysis.Rmd` file performs a time series analysis on eye-movement data collected from virtual reality video game play. The analysis focuses on the effect of time on gaze stability, measured by fluctuations in gaze points (X, Y, Z coordinates) across different VR games. The report generated from this analysis is saved as a PDF.

## Dataset Information

The dataset used for this analysis is titled "The statistics of gaze during VR gaming" and was published by Avi Aizenman et al. on Dryad. The dataset includes eye-movement recordings during VR gaming and is available at the following link:

- **Dataset Authors**: 
  - Avi Aizenman, University of California, Berkeley
  - George Koulieris, Durham University
  - Agostino Gibaldi, University of California, Berkeley
  - Vibhor Sehgal, University of California, Berkeley
  - Dennis Levi, University of California, Berkeley
  - Marty Banks, University of California, Berkeley
  - Email: avigael_aizenman@berkeley.edu
- **Published**: July 17, 2022 on Dryad
- **DOI**: [https://doi.org/10.6078/D1BB16](https://doi.org/10.6078/D1BB16)

**Citation**:
Aizenman, Avi et al. (2022). The statistics of gaze during VR gaming [Dataset]. Dryad. [https://doi.org/10.6078/D1BB16](https://doi.org/10.6078/D1BB16)

## Usage

### Prerequisites

Make sure you have the following software and R packages installed on your system:

- R
- RStudio (optional, but recommended)
- The following R packages:
  - `tidyverse`
  - `lubridate`
  - `ggplot2`
  - `forecast`
  - `tseries`

You can install the necessary R packages using the following commands in R:

```R
install.packages("tidyverse")
install.packages("lubridate")
install.packages("ggplot2")
install.packages("forecast")
install.packages("tseries")
