# Langosteira Outer Port Wave Agitation Data Repository

This repository contains wave agitation data recorded at the [Outer Port of Punta Langosteira](https://www.google.com/maps/place/43.341927,-8.507792 "Outer Port of Punta Langosteira, Spain") (A Coruña, Spain), from Oct 2024 to Jan 2025. 

## Data Sources

The data was collected using the [OBS-Buoy400 Wave Buoy model](https://obscape.com/site/products/wavebuoy/), which is designed for reliable wave and sea condition monitoring. The buoy is equipped with sensors to measure wave height, period, and other related parameters accurately.

## Location

The buoy is positioned at the [Outer Port of Punta Langosteira](https://www.google.com/maps/place/43.341927,-8.507792 "Outer Port of Punta Langosteira, Spain"), with the following geographical coordinates:

- **Latitude:** 43.341927
- **Longitude:** -8.507792

This location provides additional wave agitation data to the already existing wave radars.

## Data Overview

The dataset contains information recorded from October 2024 to January 2025. Each data point is separated by a 30-minute interval. The variables included are essential for understanding wave characteristics and are defined as follows:

### Variables:

1. **Time (UTC):** the timestamp of the recorded data in Coordinated Universal Time (UTC).

2. **Significant Wave Height (h_s) [m]:** represents the average height of the highest one-third of waves observed during the sampling period, measured in meters.

3. **Maximum Wave Height (h_max) [m]:** the maximum height of a single wave recorded during the sampling period, measured in meters.

4. **Peak Wave Period (t_p) [s]:** the period (in seconds) corresponding to the peak energy of the wave spectrum, indicating the dominant wave period.

### File details

The same dataset is provided in two formats for flexibility and ease of use:

- An excel file with the above variables as columns.
- A csv file for easy data processing using code or data analysis tools.

## Funding

- This equipment is part of the R&D&i project PID2020-112794RB-I00, funded by MICIU/AEI/10.13039/501100011033.
- FPI predoctoral grant from the Spanish Ministry of Science and Innovation [grant number PRE2021- 100141, funded by MCIN/AEI/ 10.13039/501100011033 and FSE+“Fondo Social Europeo Plus”].
- This equipment is also part of the R&D&i project PID2023-149956OB-I00, funded by MICIU/AEI/10.13039/501100011033.

<div align="center">
    <img src="img/MICIU_AEI.jpg" alt="Funding Agency Logo" width="350"  />
</div>

## Contact

For further questions or collaborations, please contact [Alberto Alvarellos](mailto:alberto.alvarellos@udc.es) or [Andrés Figuero](mailto:andres.figuero@udc.es).

