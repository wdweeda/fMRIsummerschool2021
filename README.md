# fMRIsummerschool2021
fMRI Summer School 2021, 28-30 June 2021, Leiden University

## Welcome

Welcome to the fMRI Summer School 2021! Below you will find all information necessary for the course. Including the links to the datasets used and any code. Throughout the two-day workshop we will mainly use the FMRIB Software Library (also known as FSL). FSL can be installed on any computer using Mac OS, Windows or Linux. 

## Software installation and data download
### Installing FSL
FSL can be installed using the `fslinstaller.py` script. This script can be downloaded from the [FSL Installation Website](https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/FslInstallation), by clicking on **Download FSL**. Then proceed by clicking on the installation page of your operating system. FSL runs best on Linux / Mac OS, but runs also on newer versions of Windows (from Windows 10 and up). Please make sure when installing that there are no spaces in your installation directory name (stick to the defaults when possible).

### Downloading data
For the practicals we will use several subjects from a study by [Pernet et al. (2015)](https://www.sciencedirect.com/science/article/pii/S1053811915005558). These data are available from [openneuro.org](https://openneuro.org/datasets/ds000158/versions/1.0.0) under accession number `ds000158`. We will only use the first 5 subjects from this dataset as to reduce computational load when doing the exercises. The data can be found via this link ([download dataset](https://surfdrive.surf.nl/files/index.php/s/ynIMQi5iQwRQvRb)). It requires a password that will be sent to you via e-mail. 

## Summer School program

FMRI Analysis Course
Summerschool Graduate School FSW 2021 
Location: Teams online

### Monday June 28: basics of fMRI analysis 

9.15 - 13.00 hrs: Lectures

Welcome: introduction

Lecture 01: Pre-processing and Registration, Serge Rombouts

- Visual inspection
- Motion correction
- Slice timing correction (part 1)
- Brain extraction
- Spatial filtering
- Temporal filtering
- Anatomical registration: FMRI to structural to standard space With examples of how this works in FSL

Lecture 02: Statistical analysis, Wouter Weeda

- General Linear Model basics
- Modeling of fMRI time-series with the General Linear Model 
- Hemodynamic Response Functions
- Motion parameters
- Temporal derivatives (slice timing correction part 2)
- Prewhitening
- Single-subject contrasts
- Higher-level analysis (and contrasts): Combining multiple runs and comparing groups
- Statistical Inference: Multiple comparisons, GRFT, voxelwise, cluster approach

13.00 - 14.00 hrs : Break

14.00 - 17.00 hrs: Analyse data yourself: practical session on statistical analysis with FSL. Install FSL, demo, instructions.

16.00 - 17.00 hrs: Q+A


### Wednesday June 30: advanced fMRI analysis 

9.15 - 13.00 hrs: Lectures

Lecture 03: Advanced Statistical Modeling, Wouter Weeda

- Advanced HRF models
- Single-trial analysis and connectivity
- Advanced Multiple Comparison techniques

Lecture 04: Resting state connectivity, Serge Rombouts

- Introduction resting state FMRI
- Data acquisition
- Temporal correlations with seed - ROI
- ICA networks
- Dual regression
- Graph analyses (the matrix)

13.00 - 14.00 hrs: Break

14.00 - 17.00 hrs: Analyse data yourself: ICA, denoising, group ICA


