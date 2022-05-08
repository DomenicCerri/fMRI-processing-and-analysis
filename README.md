# fMRI preprocessing with PyNIT pipeline, event-related AFNI analyses, mask-based time series extraction, and time series analyses and visualizations for simple and complex paradigms.

3D preprocessing includes motion correction, skull stripping, slice timing correction, spatial smoothing, spatial normalization of anatomical and functional images to template space, and CBV calculation (used in timeseries extraction only)

3D analyses include GLM, REML, clusterization, 3dttest++ (with and without FWE cluststim), and summation (of subject masks)

Time series analyses include baseline correction, peak-detection, quantification


# Dependencies:

AFNI (Analysis of Functinal Neuroimages) https://afni.nimh.nih.gov/pub/dist/doc/htmldoc/background_install/install_instructs/index.html

Python 2.7

PyNIT (Python Neuroimaging Toolkit) https://github.com/dvm-shlee/PyNIT.git


# Additional dependency for "fMRI-Timeseries-Complex" only:

PyNSP (Python Neuroimaging Signal Processing) https://github.com/dvm-shlee/PyNSP.git
