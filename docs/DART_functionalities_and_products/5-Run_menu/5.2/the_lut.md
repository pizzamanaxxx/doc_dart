The LUT (i.e., SQL database) can store most non image 'radiometric products': scene BOA / TOA radiance $L_{scene}(\Omega_v)$, reflectance $\rho_{scene}(\Omega_v)$ or brightness temperature $T_{B,scene}(\Omega_v)$, irradiance,… Data can be displayed and exported. The option "LUT creation" and the data to store are set in the menu "Run / LUT Properties" for a single simulation and in the menu "Sequence Launcher / … / Preferences / LUT Generation" for a sequence of simulations. (see below). In these menus, if the the LUT's option "Store only for added directions" is unset, the LUT stores {$L_{scene}(\Omega_v), \rho_{scene}(\Omega_v)$ / $T_{B,scene}(\Omega_v)$} for $\Omega_v$ in $\Delta \Omega_v=90°*360°$. The option "Store only for the angular range" sets bounds for $\Omega_v$. DART-FT always computes {$L_{scene}(\Omega_v), \rho_{scene}(\Omega_v)$ / $T_{B,scene}(\Omega_v)$} whatever LUT options, conversely to DART-Lux that computes them if it is a selected DART-Lux product or if required in the LUT, presently with 1° angular steps over 90°x360°. It can greatly increase DART-Lux computer time for scenes with very few pixels.

<center><img src="./media/creation_for_a_simulation.png"><p>*LUT: a) creation for a simulation.*</p></img></center>

<center><img src="./media/sequence_of_simulations.png"><p>*LUT:b) a sequence of simulations.*</p></img></center>

<center><img src="./media/data_to_store.png"><p>*c) data to store.*</p></img></center>

<img src="../../media/1.png" width=15/> To store or not the LUT

<img src="../../media/2.png" width=15/> To store radiance $L_{scene}(\Omega_v), \rho_{scene}(\Omega_v)$ / $T_{B,scene}(\Omega_v)$.

<img src="../../media/3.png" width=15/> Selection of data to store

<img src="../../media/4.png" width=15/> To store products per type of scene element

<img src="../../media/5.png" width=15/> To store results only for added directions.

<img src="../../media/6.png" width=15/> To store $L_{scene}(\Omega_v), \rho_{scene}(\Omega_v)$ / $T_{B,scene}(\Omega_v)$ only for $\Delta \Omega_v$

<img src="../../media/7.png" width=15/> To store Earth scene parameters calculated by the Maket module.
