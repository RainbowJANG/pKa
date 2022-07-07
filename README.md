# $pK_{a}$  $Calculation$


Take Mol No.1 as an example pKa calculation. 

RI-DSD-PBEP86/aug-cc-pVTZ in SM12 solvation model was applied.

The '*.log' files (under 'log' folder) are output files for gas phase geometry optimisation at M06-2X/6-31+G* level of theory.

- From '*.log' files, we can grep 'Thermal correction to Gibbs Free Energy' as $G_{corr}$ for the gas phase.

The '*.avtz.out' output files (under 'avtz' folder) are single point calculations for the gas phase at a higher level of theory (RI-DSD-PBEPF86/aug-cc-pVTZ).

- From these files, we can get 'FINAL SINGLE POINT ENERGY' as $E_{gas}$ for the gas phase.

The '*.smd.xyz1.out' output files (under 'sm12' folder) are single point calculations for the solutuion phase in SM12 solvation model.

- From these files, we can get '(9)  DeltaG-S(liq) free energy of  solvation' as $∆G^{*}_{solv}$.
