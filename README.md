# settlingBed2D_driftModel_densityChange
A multiphase Eulerian granular model with population balance model and a drift Model using densityChange setup.

# Software
OpenFOAM 6

# Bug
15.07.2021 Converged but it appears that driftModel implemented had no effect on system. 
-> This could be due to solid and liquid phases which are incompressible, and thus density does not change, in addition to lack of any phase change which may affect density as well. Without any density change, it is expected that there would be no effect on the system.  
