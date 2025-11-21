# Experimental Data for JGR: Oceans Submission
This repository contains the experimental data used in the paper:
"Experimental Study of Submarine Landslide Tsunami in Stratified Sand and Silt Layers on a Gentle Slope"

## Data availability
- Experimental data (TXT): GitHub repository (DOI: https://doi.org/10.5281/zenodo.17668077)
- Videos of landslide motion: Zenodo (DOI: https://doi.org/10.5281/zenodo.17667882)

## Repository Structure
- `Case_A1_time_series.txt` : Time-series data for Case A1
- `Case_A1_summary.txt` to `Case_C1_summary.txt` : Maximum and minimum water levels for each trial in Cases A1–C1
- `motion_A1.txt` to `motion_C1.txt` : Motion of sliding mass for one trial in Cases A1-C1

## Data Format
### Time-series file (Case_A1_time_series.txt)
Format:
- time (s)
- WG1, WG2, WG3, ... : wave gauges (mm)
- PP1, PP2, ... : pore pressure transducers (kPa)

### Maximum values files (Case_A1_summary.txt, etc.)
Format:
- 1, 2, 3,...: wave gauge number
- mim: minimum amplitude at each wave gauge (mm)
- max: maximum amplitude at each wave gauge (mm)

### Landslide motion files (motion_A1.txt, etc.)
Format:
- time (s)
- velocity (m/s)
- acceleration (m/s2)

### Video files
The videos showing the landslide motion are available on Zenodo:
https://doi.org/10.5281/zenodo.17667882
Files:
- A1.mp4: video used for overall results
- A1_cam1_3-5.mp4: video used to confirm formation of water film

## Notes
- Only raw data used for figures and tables in the paper are provided.
- Additional data are available from the corresponding author upon reasonable request.
