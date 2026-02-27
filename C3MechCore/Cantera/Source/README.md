# Description
The mechanism files placed in the "Source" directory are the ones used to generate Cantera-compatible mechanism files (.yaml).

Chemkin mechanisms allow setting individual parameters for specific third bodies using the keywords LOWMX/TROEMX and LOWSP/TROESP, which are used for the reaction H+O2(+M)=HO2(+M). However, since Cantera does not support these keywords, attempting to compile the mechanisms in the Chemkin folder for Cantera will result in errors.

To avoid this, the mechanism files in this folder define H+O2(+N2)=HO2(+N2) and H+O2(+HE)=HO2(+HE)
separately, and also split CH3+H(+M)=CH4(+M) into an explicit (+HE) form for Cantera compilation.
Due to this, reaction counts differ between CHEMKIN-Pro and Cantera-compatible mechanisms. Reported
reaction counts in this repository use the Cantera-compatible mechanism as reference.
