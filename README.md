# Opacity of strongly magnetised high temperature plasma

The repository contains the files with the grid Rosseland opacities calculated across and along the magnetic field, 
computed with various contribution of electron-positron pairs. 
Calculatios are discribed in a paper **"Mean opacities of a strongly magnetized high temperature plasma" by Suleimanov et al., 2022, MNRAS** 
[[see arXiv]](https://arxiv.org/abs/2210.09995).

The opacities represented in different files are computed under different assumptions about contribution of electron-positron pair. 
In particular, the files contained in archives **ross1.zip** and **ross2.zip** correspond to the opacities across and along the field respectively  with the pairs in thermodynamic equilibrium and opacities due to pair creation taken into account. 
The files contained in archives **ross3.zip** and **ross4.zip** correspond to the opacities across and along the field respectively with no pairs, but the opacities due to pair creation taken into account. 
The files contained in archives **ross5.zip** and **ross6.zip** correspond to the opacities across and along the field respectively  computed without pairs participation at all.

Every archive file contains information about the Rosseland opacities calculated for
- 14 values of magnetic fields: $lg(B) = 10.5, 11.0, 11.5, 11.75, 12.0, 12.25, 12.5, 12.75, 13.0, 13.25, 13.5, 14.0, 14.5, 15.0$ (magnetic field strength $B$ is given in units of **Gauss**),
- 19 values of mass density $\rho$ (in units of **g/cm^3**), from $lg(\rho)$ = -6 to 3 with the step $0.5$, 
- 85 values of temperature, from $lg(T) = 0$ to $2.52$ with the step $0.03$ (the temperature is given in **keV**).

Every archive file is organised as a set of 14 two-dimensional tables of the opacities collected in separate data files named like
**ross1_b1175.dat**. 
Every two-dimensional table is computed for the magnetic field strength marked in the file name.
In the example above, the magnetic field strength corresponds to $lg(B) = 11.75$. 
Each table consists of 85 rows corresponding to the grid temperatures and 21 columns. 
In the first column, the temperature in units of keV is presented, in the second column, the values  $lg(T)$ is presented, 
and in the rest columns the values of the Rosseland mean opacities for 19 values of the plasma density are presented, 
starting with $lg(\rho)=-6$ (third column).
