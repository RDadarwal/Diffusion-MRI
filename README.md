# Diffusion-MRI (dMRI)
These jupyter notebooks include diffusion MRI data analysis in order to calculate __Diffusion Tensor Imaging (DTI)__, __Diffusion Kurtosis Imaging (DKI)__ and __Neurite Orientation Dispersion and Density Imaging (NODDI)__ parametric maps.
dMRI pre-processing jupyter notebook includes diffusion MRI data __denoising__ using DIPY NLMEANS, susceptibility-induced distortion correction using FSL __TOPUP__ and eddy current-induced distortion and motion correction using FSL __EDDY__.

Note that, estimation of DKI and NODDI parametric maps requires at least two different b-values. 

### Dependencies
Python dependencies to use these jupyter notebooks are:
* dipy (https://dipy.org/)
* nipype (https://nipype.readthedocs.io/en/latest/)
* FSL (https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/FSL)
* AMICO (https://github.com/daducci/AMICO)
* numpy
* nibabel
