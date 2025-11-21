# A Strong Cold Front Climatology for Eastern Colorado, 1950–2022

This repository contains supporting data and Python analysis scripts for the
project **“A Strong Cold Front Climatology for Eastern Colorado, 1950–2022.”**
It accompanies the manuscript that documents the climatology, environmental
composites, and forecast evaluation of strong cold fronts impacting eastern
Colorado.

The datasets provided in Project_Data/ are processed, derived products created specifically for this study (e.g., front lists, composites, teleconnection-labeled cases).
They may be used for academic research, teaching, or reproducibility efforts. Please credit this project and repository when using them.

---

## Repository Structure

- `Project_Data/`
  - Processed datasets used in the analysis (e.g., front lists such as All, LP, HP, composite
    fields, and other derived variables).
  - These are *analysis-ready* files; large/raw source datasets from ERA5 and are **not** included due to size and distribution restrictions.

- `Python_Notebooks/`
  - Jupyter notebooks used to:
    - build the strong cold front climatology from 1950-2022,
    - compute and visualize environmental composites (temp, winds, FGEN, MSLP, etc.),
    - evaluate statistics and teleconnection relationships such as AO, ENSO, and MJO,
    - generate figures shown in the manuscript.

- `README.md`
  - Overview of the project and instructions for use.

---

## Requirements

The notebooks primarily use the standard scientific Python stack, including:

- `xarray`, `numpy`, `pandas`
- `matplotlib`, `cartopy`
- `metpy`
- `scipy`

You can install these with `conda` or `pip` in your preferred environment.
See the top of each notebook for any additional, notebook-specific
dependencies.

---

## Getting Started

1. **Clone the repository**

   ```bash
   git clone https://github.com/ZachMichael477/A-Strong-Cold-Front-Climatology-for-Eastern-Colorado-1950-2022.git
   cd A-Strong-Cold-Front-Climatology-for-Eastern-Colorado-1950-2022
