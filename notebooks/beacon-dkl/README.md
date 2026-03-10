# Repository for the work: Novelty-Driven Target-Space Discovery in Automated Electron and Scanning probe Microscopy

[arXiv-link-coming-soon]

Folders and files:
- data/preacq_data: contains the preacquired STEM-EELS
- data/STEM-live-data: STEM-EDX live experiment
- notebooks/On_preacq_data
    - 6 notebooks pertaining to EELS and PFM data doing DKL with 3 acquisiton functions
        - EI
        - UCB
        - BEACON
    - 1 notebook on postprocessing output data - Postprocess-and-generate-plots.ipynb

- notebooks/On_live_instrument
    - 3 notebooks pertaining to STEM-EDX
        - EI
        - UCB
        - BEACON
    - 1 notebook on postprocessing output data - Postprocess-and-generate-plots.ipynb

Note: to run the live notebook you need to setup : https://github.com/pycroscopy/pyAutoMic/tree/main/TEM/stemOrchestrator