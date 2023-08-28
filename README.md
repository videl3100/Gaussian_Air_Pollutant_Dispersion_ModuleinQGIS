# Gaussian_Air_Pollutant_Dispersion_ModuleinQGIS
Hi! In this tutorial, we will learn how to create a Gaussian pollutant dispersion model using QGIS.

GAUSSIAN DISPERSION MODEL
This model is used to evaluate the effect of point emissions (i.e. from a fixed or stationary point, such as a stack, smoke tower, or fan). It locates the point emission source, in this case study we will use a stack, in a coordinate system (x,y,z), where the x-axis goes in the wind direction, the y-axis is the perpendicular direction and the z-axis represents the height, this gives us the concentration of the pollutant at any point in space (x,y,z).
 The pollutant is emitted at a height z=H, where H is known as the effective stack height, which is equal to the height of the stack, plus the height to which the plume (smoke cloud) rises, because it is a hot gas it tends to float, along with the vertical movement it has when it leaves the stack. This model assumes that the smoke plume moves in the direction of the wind, which gives it a velocity and disperses in the directions perpendicular to it, on the y-z axis.
