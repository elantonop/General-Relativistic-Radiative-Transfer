Code -> Setup and run the General Relativistic Radiative Transfer scheme 

1. Libraries -> Import Required Libraries
2. Functions -> Define Functions
4. GRRT -> Import General Relativistic Radiative Transfer Function
5. Setup -> Determine the simulation parameters / Run the General Relativistic Radiative Transfer scheme

   
            File Name: HotSpot_Emission.txt
   
            First Line: Parameter Labels
   
            File Output: t_obs -> Observation Time
                         x0_ray / y0_ray / z0_ray -> Pixel Coordinates
                         t_left_plasmoid / r_left_plasmoid / theta_left_plasmoid /	phi_left_plasmoid /	pr_left_plasmoid / ptheta_left_plasmoid -> Boyer-Lindquist Coordinates & Momenta when the Photon ray exits the Hot Spot Radiative Sphere 
                         tauv_left_plasmoid /	Iv_left_plasmoid -> Optical Depth & Normalized Intensity when the Photon ray exits the Hot Spot Radiative Sphere
                         g_redsh -> Calculated Redshift
                         in_plasmoid -> 1: Photon ray hit the Hot Spot surface / 0 : Photon ray did not hit the Hot Spot surface
             Data separation: \t
             Last Three Lines: Simulation Parameters
              
Plotting -> Plot the results

1. Libraries -> Imports Required Libraries
2. Plots -> Plot the Hot Spot image /The colorbar corresponds to the Normalized Intensity / Variable t_plot determines the desired snapshot
