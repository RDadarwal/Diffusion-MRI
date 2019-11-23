# Diffusion-MRI
These jupyter notebooks include diffusion MRI data analysis in order to calculate Diffusion Tensor Imaging (DTI), Diffusion Kurtosis Imaging (DKI) and Neurite Orientation Dispersion and Density Imaging (NODDI) parametric maps.
Pre-processing includes diffusion MRI data denoising, susceptibility-induced distortion correction using FSL TOPUP and eddy current-induced distortion and motion correction using FSL EDDY.

\*Note that, estimation of DKI and NODDI parametric maps requires at least two different b-values.\* 

### Dependencies
Python dependencies to use these jupyter notebooks are:
* dipy (https://dipy.org/)
* nipype (https://nipype.readthedocs.io/en/latest/)
* FSL (https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/FSL)
* AMICO (https://github.com/daducci/AMICO)
* numpy
* nibabel
