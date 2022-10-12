# Opacity of strongly magnetised high temperature plasma

The repository contains the files with the grid Rosseland opacities calculated across and along the magnetic field, 
computed with various contribution of electron-positron pairs. 
Calculatios are discribed in a paper **"Mean opacities of a strongly magnetized high temperature plasma" by V.F.Suleimanov et al., 2022, MNRAS**.

Files in **ross1.zip** and **ross2.zip** correspond to the opacities across and along the field correspondingly with the pairs 
in thermodynamic equilibrium and opacities due to pair creation taken into account. 
Files **ross3.zip** and **ross4.zip** correspond to the opacities across and along the field correspondingly with no pairs, 
but the opacities due to pair creation taken into account. 
Files **ross5.zip** and **ross6.zip** correspond to the opacities across and along the field correspondingly computed without pairs participation at all.

Every file consists the Rosseland opacities for 14 values of magnetic fields:
$lg(B) = 10.5, 11.0, 11.5, 11.75, 12.0, 12.25, 12.5, 12.75, 13.0, 13.25, 13.5, 14.0, 14.5, 15.0$, ($B$ is give in units Gauss), 
and 
for 19 values of density ($\rho$), from $lg(\rho)$ = -6 to 3 with the step $0.5$, 
and 
for 85 values of temperature, from $lg(T) = 0$ to $2.52$ with the step $0.03$.

Every file organizes as a following of 14 two-dimensional tables of the opacities collected in separate data files named like
**ross1_b1175.dat**. Every two-dimensional file is computed for the magnetic field strengt marked in the file name.
In the example above, the magnetic field strength corresponds to $lg(B) = 11.75$. 
Every two-dimensional file consists 85 rows corresponding to the grid temperatures and 21 columns. 
In the first column the temperature in keV is presented, in the second one the values lg(T) is presented, 
and in the rest columns the values of the Rosseland mean opacities for 19 values of the plasma density are presented, 
starting with $lg(\rho)=-6$ (third column).
