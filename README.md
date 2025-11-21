# A Strong Cold Front Climatology for Eastern Colorado, 1950–2022

This repository contains supporting data and Python analysis scripts for the
project **“A Strong Cold Front Climatology for Eastern Colorado, 1950–2022.”**
It accompanies the manuscript that documents the climatology, environmental
composites, and forecast evaluation of strong cold fronts impacting eastern
Colorado.

---

## Repository Structure

- `Project_Data/`
  - Processed datasets used in the analysis (e.g., front lists such as All, LP, HP, composite
    fields, and other derived variables).
  - These are *analysis-ready* files; large/raw source datasets from ERA5 and are **not** included due to size and distribution restrictions.

- `Python_Notebooks/`
  - Jupyter notebooks used to:
    - build the strong cold front climatology,
    - compute and visualize environmental composites,
    - evaluate statistics and teleconnection relationships,
    - create all figures shown in the manuscript.

- `README.md`
  - This file.

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
