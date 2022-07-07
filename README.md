# $pK_{a}$  $Calculation$



RI-DSD-PBEP86/aug-cc-pVTZ in SMD and SM12 solvation models were applied.

The '*.log' files (under 'log' folder) are output files for gas phase geometry optimisations at M06-2X/6-31+G(d) level of theory.

- From these files, we can grep 'Thermal correction to Gibbs Free Energy' as $G_{corr}$ for the gas phase.

The '*.avtz.out' output files (under 'avtz' folder) are single point calculations for the gas phase at a higher level of theory (RI-DSD-PBEPF86/aug-cc-pVTZ).

- From these files, we can get 'FINAL SINGLE POINT ENERGY' as $E_{gas}$ for the gas phase.

The '*.smd.log' output files (under 'smd' folder) are solution phase geometry optimisations at M06-2X/6-31+G(d) level of theory in SMD solvation model.

- From these files, we can grep the last 'SCF Done' energy as as $∆G^{*}_{solv}$.

The '*.smd.xyz1.out' output files (under 'sm12' folder) are single point calculations for the solutuion phase at M06-2X/6-31+G(d) level of theory in SM12 solvation model.

- From these files, we can grep '(9)  DeltaG-S(liq) free energy of  solvation' as $∆G^{*}_{solv}$.
