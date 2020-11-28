# Heat-Transfer-Model-of-Granular-Matter-Inside-The-Rotating-Drum-Using-PFC3D
DEM Model using PFC3D Version 4.0 of Heat transfer model (FISH Language)
The drum walls codes is modified using FORTRAN with speficification diameter of the drum (D)=100 mm and depth(L)=10 mm
The circumferance of the drum is devided into 64 wall segments.
The 32 wall segments is rechieved the heat energy whilst others not.
The 32 wall segments that getting the heat energy is called the heating walls then others are the non-heating walls
The particle diameter of granular is 5 mm, while particle diameter of glued particle to non-heating walls is 0.5 mm
This codes is an example for one pattern model and for other pattern you can modified in ParticleGluedWall.Dat file.
When you run this file, the PFC3D generate lots of ODS file related with ParticleID,position of particle in 3D repectively (x,y,z), translational velocity in x,y,z, rotational velocity in x,y,z and temperature value of every particle. Also, the simulation generates the WallPressure data in ODS. You can open ODS files directly vie excel.
The post-processing of this works is conducted with Python.
The details results you can look at in figure and plots.
