It gets maps of DART parameters ($\rho_{ground}$, LAI,…) from a set of remote sensing spectral images using pre-computer LUT where M DART parameters vary (cf Module_User_Manual). These M parameters are set to:

- Fixed with the same value for all images: the parameter value is specified.
- Free: the inversion computes the parameter value.
- Not fixed - Spectral - 1, 2 or 3 parameters. It allows one to define a spectral quantity that is a linear combination of 1, 2 or 3 spectra. For example, ground reflectance can be defined a linear combination of spectra $\rho_i(\lambda)$ with I free parameters $a_{\lambda}: \rho_{ground}(l)=\sum_{i=1}^I a_{\lambda}.\rho_i(\lambda)$ with $I \in [1\:;\:3]$
