# Anxiety disorders - Brain map fMRI data
## Home assignment - Programming for Psychologist - 2024/2025

**Name** Edoardo Galli\
**Date** 29/11/2024\
**Student number** 2859426

**Data source** [https://neurosynth.org/analyses/terms/anxiety%20disorders/]


### Description
My project visualizes the correlation between brain activity and **anxiety disorders** using fMRI data sourced from Neurosynth (see link). The fMRI  data highlight brain regions with strong statistical associations to anxiety disorders (spatial context), derived from a meta-analysis of 95 studies. Moreover, the project includes a histogram analysis, providing insight into the distribution of functional activation values.

### Files and notebook used

*Anatomical Data*
- Structural MRI scan of the human brain (anatomical.nii.gz).
- Functional Data: Statistical map showing brain regions associated with anxiety disorders (uniformity_test.nii.gz).

*Notebook*

- Jupiter notebook containing the Python code for processing, visualizing, and analyzing the fMRI data.

*Outputs*

- Brain Map Visualization fMRI
- Histogram with voxel value

## **Python Packages used:**
- os: file handling & directory operations
- nibabel: reading neuroimaging data files
- matplotlib: plotting histogram
- nilearn: visualizing fMRI data
