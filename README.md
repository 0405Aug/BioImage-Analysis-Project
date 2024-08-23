# Bioimage Analysis Project

## Overview

This project involves the analysis of biological image data using various image processing techniques. The Jupyter notebook included in this repository contains code for image filtering, segmentation, statistical analysis, and visualization.

There is a detailed Report on this project, that have explanations and results for this project.

## Notebook Description

### Jupyter Notebook

- **Filename**: `Bioimage_Analysis.ipynb`
- **Description**: This notebook performs image filtering, segmentation, statistical tests, and visualization for biological image data.

### Key Sections

1. **Image Filtering**:
   - Applies Gaussian and median filters to smooth the images.
   - Utilizes top-hat filtering to enhance certain features.
   - Use a combination od Difference of Gaussian and Gaussian filtered image

2. **Segmentation**:
   - Implements Voronoi Otsu Threshold Labelling for image segmentation.
   - Applies APOC for object segmentation using pre-trained machine learning models.
3.**BlandAltmann Analysis** : to compare the segmentation methods

4. **Statistical Analysis**:
   - Performs t-tests to compare various parameters (Area, Mean intensity, perimeter, circularity) between different sample groups.
   - 
5. **Visualization**:
   - Creates violin plots to visualize the distribution of different parameters.
   - Displays statistical p-values on the plots for interpretation.
6.**Dimensionality Reduction**: UMAP
