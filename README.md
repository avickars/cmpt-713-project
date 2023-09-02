# Project Readme

This repository contains the code for the project for CMPT 713 at Simon Fraser University.  To read the project report, please 
see `report.pdf`.  For code documentation, please see `project.ipynb` that contains details on the prerequisites for
running this repository and the structure of this repository.  To reproduce the figures and results in `report.pdf`
please first read `project.ipynb` so that you understand the structure of this repository, then see
`output.ipynb` that contains detailed instructions and code for reproducing the results.

This repository contains several surface level scripts that are:
- `download_models.py` - This script is used in both `project.ipynb` and `output.ipynb` and downloads the trained models for this project from Google Drive.
- `download_output.py` - This script is used in both `project.ipynb` and `output.ipynb` and downloads the data and results for this project from Google Drive.
- `zip_output.py` - This script zips the data and results for this project so that users can download it at a later date.
- `project.ipynb` - Documentation on the prerequisites and structure of this repository.
- `output.ipynb` - Documentation and code to reproduce the results shown in `report.pdf`.
- `chrome-extension` - The documentation and code demonstrate the usage of a BERT model to perform real-time sentiment analysis through a Chrome extension.