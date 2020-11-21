# Diffusion-MRI (dMRI)
These Jupyter notebooks include diffusion MRI data analysis to calculate __Diffusion Tensor Imaging (DTI)__, __Diffusion Kurtosis Imaging (DKI)__, __Neurite Orientation Dispersion and Density Imaging (NODDI)__, __Single-Shell 3-tissue Constrained Spherical Deconvolution (SS3T-CSD)__, and __Multi-Shell Multi-Tissue Constrained Spherical Deconvolution (MSMT-CSD)__ modeled parametric maps.

__Pre-processing__ Jupyter notebook includes data __denoising__ using DIPY, susceptibility-induced distortion correction using FSL __TOPUP__ and eddy current-induced distortion and motion correction using FSL __EDDY__.

Note: estimation of DKI, NODDI, and MSMT-CSD modeled parametric maps require diffusion-weighted MRI data acquired for at least two b-values (e.g. 1000, 2000).

### Dependencies
Dependencies to use these Jupyter notebooks are:
* DIPY (https://dipy.org/)
* Nipype (https://nipype.readthedocs.io/en/latest/)
* FSL (https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/FSL)
* AMICO (https://github.com/daducci/AMICO)
* MRtrix3 (https://www.mrtrix.org/)

### Citation
Messinger, A., Sirmpilatze, N., Heuer, K., Loh, K.K., Mars, R.B., Sein, J., Xu, T., Glen, D., Jung, B., Seidlitz, J., Taylor, P., Toro, R., Garza-Villarreal, E.A., Sponheim, C., Wang, X., Benn, R.A., Cagna, B., Dadarwal, R., Evrard, H.C., Garcia-Saldivar, P., Giavasis, S., Hartig, R., Lepage, C., Liu, C., Majka, P., Merchant, H., Milham, M.P., Rosa, M.G.P., Tasserie, J., Uhrig, L., Margulies, D.S., Klink, P.C., 2020. __A collaborative resource platform for non-human primate neuroimaging__. NeuroImage 117519. https://doi.org/10.1016/j.neuroimage.2020.117519

### Example dataset: 
In vivo diffusion MRI data (__Macaca mulatta brain__ scanned at Siemens 3T) provided by the Aix-Marseille Université at the __PRIMatE Data Exchange__ (http://fcon_1000.projects.nitrc.org/indi/indiPRIME.html).

![](dMRI_maps.png)
![](MSMT-CSD_maps.png)
