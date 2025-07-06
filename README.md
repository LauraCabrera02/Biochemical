This repository contains a Python notebook developed for the analysis and visualization of biogeochemical variables from ocean model output in NetCDF format. The notebook provides an introduction to handling oceanographic data including temperature, salinity, oxygen, and nutrient concentrations.
📑 Contents

The notebook Bio_lab.ipynb covers the following:

    📦 Reading NetCDF files using xarray

    🌊 Extracting oceanographic and biogeochemical variables

    📈 Plotting spatial distributions of variables at specific depths

    📊 Computing and visualizing zonal means of selected variables

    📍 Producing maps and cross-sections using Matplotlib and Cartopy

📁 Repository Structure

Biochemical/
├── Bio_lab.ipynb       # Main notebook for biogeochemical data analysis
└── README.md           # Project description

📊 Data

The notebook works with NetCDF files containing variables such as:

    Temperature

    Salinity

    Oxygen

    Nutrients (e.g. nitrate, phosphate)

    📌 Data files should be placed in the same directory as the notebook or paths adjusted accordingly.

🛠️ Requirements

The following Python libraries are needed to run the notebook:

    xarray

    numpy

    matplotlib

    cartopy

    netCDF4

Install them via:

pip install xarray numpy matplotlib cartopy netCDF4

📌 Notes

    This notebook is intended for academic purposes and serves as an introduction to biogeochemical data analysis from ocean models.

    The figures generated include both horizontal maps at specific depths and zonal mean sections (latitude vs depth).

📖 Credits

Developed by Laura Fernanda Cabrera Zamora, Evans Addo, and Armand Diffo
Year: 2025
Project: Biogeochemical Data Analysis Lab — Earth System Modelling coursework
