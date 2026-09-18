# Colour-your-own-universe

Python pipelines and computational workflows for automated data retrieval, image processing, and visual analysis of deep-sky astronomical targets using Google Colab. Designed for processing multi-band observational datasets, rendering high-resolution celestial objects, and performing reproducible quantitative space science research.


# Visual Analysis & Processing Pipeline for Astronomical Targets

An open-source Python workflow developed to automate the retrieval, processing, and high-resolution rendering of deep-sky astronomical targets. This project was conducted within a scientific community setting, implementing computational techniques to render multi-band observational datasets using Google Colab.

---

## Overview & Purpose

This repository houses the computational pipeline used to process and render 15 deep-sky targets. The project focuses on taking raw multi-band image data and applying contrast stretching, color mapping, and visual enhancement algorithms to produce clear spatial visualizations of celestial structures.

### Key Objectives
* Automate image processing pipelines for deep-sky target datasets within Google Colab.
* Apply multi-band color composition and contrast-stretching transformations.
* Standardize visual output for accurate comparative analysis across multiple targets.

---

## Computational Methodology

The rendering pipeline processes target data through several distinct quantitative steps:

1. **Data Ingestion:** Fetching multi-spectral image layers for target astronomical objects.
2. **Preprocessing & Normalization:** Applying logarithmic/asinh scaling and background noise suppression to enhance faint structural features.
3. **Color Composition:** Mapping individual wavelengths to RGB color channels to create true-color/false-color visual representations.
4. **Export & Standardization:** Automatically saving high-resolution outputs for analysis and documentation.

---

## Target Gallery

| Target | Visual Output | Target | Visual Output |
| :--- | :---: | :--- | :---: |
| **Andromeda Galaxy (M31)** | <img src="images/RGB_Andromeda_Galaxy_M31.png" width="220"> | **Bode's Galaxy (M81)** | <img src="images/RGB_Bode's_Galaxy_M81.png" width="220"> |
| **Crab Nebula (M1)** | <img src="images/RGB_Crab_Nebula_M1.png" width="220"> | **Dumbbell Nebula (M27)** | <img src="images/RGB_Dumbbell_Nebula_M27.png" width="220"> |
| **Globular Cluster M15** | <img src="images/RGB_Globular_Cluster_M15.png" width="220"> | **Hercules Cluster (M13)** | <img src="images/RGB_Hercules_Globular_Cluster_M13.png" width="220"> |
| **Lagoon Nebula (M8)** | <img src="images/RGB_Lagoon_Nebula_M8.png" width="220"> | **Orion Nebula (M42)** | <img src="images/RGB_Orion_Nebula_M42.png" width="220"> |
| **Pleiades (M45)** | <img src="images/RGB_Pleiades_M45.png" width="220"> | **Ring Nebula (M57)** | <img src="images/RGB_Ring_Nebula_M57.png" width="220"> |
| **Sombrero Galaxy (M104)** | <img src="images/RGB_Sombrero_Galaxy_M104.png" width="220"> | **Triangulum Galaxy (M33)** | <img src="images/RGB_Triangulum_Galaxy_M33.png" width="220"> |
| **Trifid Nebula (M20)** | <img src="images/RGB_Trifid_Nebula_M20.png" width="220"> | **Veil Nebula (NGC 6992)** | <img src="images/RGB_Veil_Nebula_NGC_6992.png" width="220"> |
| **Whirlpool Galaxy (M51)** | <img src="images/RGB_Whirlpool_Galaxy_M51.png" width="220"> | | |

---

## Scientific Community Experience & Key Learnings

Working on this project within a scientific community environment provided practical hands-on experience in computational space science and data workflows:

* **Algorithmic Development:** Developed custom Python scripts to optimize contrast and channel balancing across varying signal-to-noise ratios.
* **Reproducible Workflows:** Engineered the workflow in Google Colab to ensure all image transformations are easily executable, modular, and fully reproducible by peers.
* **Community Collaboration:** Engaged in peer review, feedback iterations, and collective problem-solving to refine visual outputs and algorithmic consistency.

---

## Getting Started

### Running in Google Colab
1. Download the `.ipynb` notebook from this repository.
2. Open [Google Colab](https://colab.research.google.com/) and upload the notebook.
3. Run all cells sequentially to execute the image rendering pipeline.

### Prerequisites
* Python 3.x
* `numpy`
* `matplotlib`
* `astropy` (if applicable)
* `PIL` / `OpenCV`

---

## License

Distributed under the MIT License. See `LICENSE` for more information.
