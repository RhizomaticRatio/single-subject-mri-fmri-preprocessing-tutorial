# Single-Subject MRI and fMRI Preprocessing Using Nilearn

## Overview
This repository contains a Jupyter Notebook that demonstrates the preprocessing steps for a single-subject MRI and fMRI dataset using **Nilearn**, a Python package for neuroimaging data analysis. The goal of this notebook is to illustrate fundamental preprocessing steps rather than provide a fully standardized pipeline.

## Features
- **MRI Preprocessing**: Brain extraction, bias field correction, tissue segmentation (atlas-based).
- **fMRI Preprocessing**: Motion correction, slice-timing correction, spatial normalization.
- **Parcellation**: Extracting region-wise time-series using an atlas.
- **Overlay Visualization**: fMRI activation maps overlaid on anatomical images.

## Important Notes
This notebook is **not** intended to be a fully precise or clinically validated preprocessing pipeline. Instead, it serves as an educational demonstration. For standardized and robust preprocessing, consider using:
- **FMRIPrep** (for fMRI preprocessing) - [Link](https://fmriprep.org/)
- **SPM** (Statistical Parametric Mapping) - [Link](https://www.fil.ion.ucl.ac.uk/spm/)
- **FreeSurfer** (Cortical Surface Reconstruction) - [Link](https://surfer.nmr.mgh.harvard.edu/)
- **AFNI** (Advanced fMRI Processing) - [Link](https://afni.nimh.nih.gov/)
- **ANTs** (Image Registration) - [Link](https://stnava.github.io/ANTs/)

## Dependencies
Make sure to install the required Python libraries before running the notebook:
```bash pip install nilearn nibabel numpy matplotlib```

## License
This project is intended for academic and research purposes. Feel free to use and modify it with proper attribution.

-----
Contributions are welcome!

If you find any issues or have suggestions, feel free to:

 Open an Issue |  Submit a Pull Request

## 📞 Contact

📧 Oğulcan ULU

ogulcan.ulu7@gmail.com / ogulcan.ulu@studenti.unipd.it
