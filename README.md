# las-file-analysis
A Python-based Jupyter notebook for petrophysical and geomechanical analysis of the TU Delft geothermal well (DEL-GT-01), using well log data in LAS format.
What this notebook does

Reads and parses LAS files using lasio
Plots wireline logs: Gamma Ray, P- and S-wave slowness, bulk density
Computes P-wave (Vp) and S-wave (Vs) velocities from sonic logs
Builds formation top intervals for the Dutch stratigraphic column
Estimates vertical stress (Sv), minimum horizontal stress (Shmin), and maximum horizontal stress (SHmax)
Constructs a stress polygon to define the allowable stress space
Performs near-wellbore stress analysis: hoop and radial stress calculations with tensile and shear failure criteria (interactive widget)
Integrates core sample data (UCS and triaxial tests) with log-derived elastic properties

Data used

LAS files from the DEL-GT-01 geothermal well, TU Delft campus
Directional survey file (Excel)
Core measurements (Vp, Vs, density from UCS and triaxial tests)
