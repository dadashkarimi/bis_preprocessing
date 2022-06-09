# BIS Processing Pipeline


## Getting Started

### Preprequisites

1. Required software: BIS (legacy), FSL, AFNI, SPM, Matlab

2. Data must be in BIDS format (e.g., subID/session1/func/task1\_run1.nii.gz, subID/session1/anat, etc.)

### Overview

> Step 1. Skull stripping (optiBET)

> Step 2. Nonlinear registration of subject anatomicals to common space (BIS)

> Step 3. Slice time correction (SPM)

> Step 4. Motion correction (SPM)

> Step 5. Linear registration of mean functionals to subject anatomicals (BIS)

> Step 6. Final check of previous steps

> Step 7. Final Study Processing (GLM, connectivity, etc; BIS) 

### Usage

1. Edit paths and parameters in config/cfg.sh

2. Run `python preprocessing.py`

