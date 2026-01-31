# Landslide Map (KMZ/KML) — for Google Earth Pro

This repository publishes landslide-related geospatial data (KMZ/KML) intended for Google Earth Pro on desktop.  
**Supported OS:** Windows / macOS / Linux (mobile Google Earth apps are not supported)

## Usage
- Google Earth Pro (official): <https://www.google.com/earth/about/versions/#download-pro>  
- Download the KMZ/KML from this repository and open it by double-clicking, or via **File → Open** in Google Earth Pro.  
  For installation details and system requirements, refer to the official page above.

## Data Contents
- **a#_dfm_roi** — Regions where topographic features suggest landslides based on **northbound** ALOS (“Daichi”) SAR observations  
  - `#=01`: based on observations on 2019-11-22 and 2021-11-19  
  - `#=02`: based on observations on 2019-11-22 and 2022-12-02  
  - `#=03`: based on observations on 2021-11-19 and 2022-12-02
- **b#_dfm_roi** — Same as above but based on **southbound** ALOS SAR observations  
  - `#=01`: based on observations on 2019-11-05 and 2021-08-10  
  - `#=02`: based on observations on 2019-11-05 and 2023-02-21  
  - `#=03`: based on observations on 2021-08-10 and 2023-02-21
- **Landslide Map** — Areas interpreted as landslide traces by NIED  
- **lodges.kmz** — Locations of Sawarajima Lodge, Niken-goya Lodge, and Senmai Hut

> Reference: NIED J-SHIS Landslide Map <https://www.j-shis.bosai.go.jp/landslidemap>

## License
The data is licensed under **Creative Commons Attribution–NonCommercial 4.0 International (CC BY-NC 4.0)**.  
See `LICENSE.md` and `LICENSE.en.md` for details.

- Copyright: © 2025 **Kazuyoshi Nanjo** — **Natural Disaster Research Section, Global Center for Asian and Regional Research, University of Shizuoka**

## Attribution (example)
Data provider: **Kazuyoshi Nanjo — Natural Disaster Research Section, Global Center for Asian and Regional Research, University of Shizuoka**  
Source: <https://github.com/KazuNanjo/shizuoka-landslide-kmz/>  
License: **CC BY-NC 4.0** (<https://creativecommons.org/licenses/by-nc/4.0/>)

## Commercial Use
For for-profit use inquiries, contact **nanjo[at]u-shizuoka-ken.ac.jp**.
