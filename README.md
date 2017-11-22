# Oumuamua
## The codes and data for the paper titled "`Oumuamua as a messenger from the Local Association"

The codes below are written in R and require R environment and relevant packages to run. 

"integrator_v4.R" and "function_orbit_v6.R" contain various functions. 

"prepare_id.R" is to convert observables to the 6D initial conditions of stars. It calls "transform.R" which is to transform observables into initial 6D state vectors in Galactocentric coordinate system. 

"scattering_experiment.R" is the main code to integrate stellar orbits. It calls "encounter_tide.R" which is to simulate the orbits of stars. 

"plot_scattering.R" is to save and visualize the output from "scattering_experiment.R". 

"make_light_curve.R" is to convert apparent magnitudes into absolute magnitudes. 

'plot_denc_venc.R' is for Figure 1. 

"plot_paper.R" is the code for Figure 2.

"paper_table.R" is to produce Table 1 and save the encounter data. 

