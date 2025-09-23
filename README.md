# uiSNR Maps in the torso of realistic body models

This repository contains uploaded **ultimate intrinsic SNR (uiSNR)** maps generated from electromagnetic simulations using the Duke and Ella body models from the Virtual Family (IT'IS Foundation, Zürich, Switzerland) [1-3]. These body models were exported as voxel models with 3 mm isotropic resolution with various types of tissues. Simulations were performed at field strengths of 0.55 T, 1.5 T, 3 T, 5 T, 7 T, 10.5 T, 11.7 T, and 14 T. At each field strength, frequency-dependent values of permittivity and conductivity[4] were assigned to different tissues in the body models.

- EM bases simulations were conducted according to Guerin et al.[5]

- For the Ella model, simulations were performed using the complete body model together with a fully enclosing dipole cloud

- For the Duke model, the truncated model (from the neck to the thighs) was employed, and a circumferential dipole cloud was arranged. The optimal SNR calculated with the truncated model and the circumferential dipole cloud provides an estimate of the uiSNR specifically in the torso region. 

- uiSNR maps were calculated with 3000 random EM bases as: $B_0^2 \sqrt{B_1^{-H} (\mathbf{r}) \Psi^{-1} B_1^- (\mathbf{r})}$ (Coefficients were omitted)

- The maps in the folders are of the term $\sqrt{B_1^{-H} (\mathbf{r}) \Psi^{-1} B_1^- (\mathbf{r})}$ 

## References
[1] https://itis.swiss/virtual-population/virtual-population/overview/

[2] Christ A, Kainz W, Hahn EG, et al. The Virtual Family-development of surface-based anatomical models of two adults and two children for dosimetric simulations. Phys Med Biol. Jan 21 2010;55(2):N23-N38. doi:10.1088/0031-9155/55/2/N01

[3] Gosselin MC, Neufeld E, Moser H, et al. Development of a new generation of high-resolution anatomical models for medical device evaluation: the Virtual Population 3.0. Phys Med Biol. Sep 21 2014;59(18):5287-5303. doi:10.1088/0031-9155/59/18/5287

[4] Hasgall PA, F. Di Gennaro, C. Baumgartner, E. Neufeld, B. Lloyd, M. C. Gosselin, D. Payne, A. Klingenböck, N. Kuster. IT’IS Database for Thermal and Electromagnetic Parameters of Biological Tissues. doi:10.13099/VIP21000-04-1 Accessed 22 Feb 2022. https://itis.swiss/virtual-population/tissue-properties/database/dielectric-properties

[5] Guerin B, Villena JF, Polimeridis AG, et al. The ultimate signal-to-noise ratio in realistic body models. Magnetic Resonance in Medicine. Nov 2017;78(5):1969-1980. doi:10.1002/mrm.26564

## Contact
For questions or collaborations, please contact:  yuting.wang@dkfz-heidelberg.de
