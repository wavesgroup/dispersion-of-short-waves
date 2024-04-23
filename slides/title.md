<section>

# Dispersion of short waves riding on longer waves

_Milan Curcic_


_Department of Ocean Science, University of Miami_

_Frost Insitute for Data Science & Computing, University of Miami_

_WISE 2024, Cargèse, France_
</section>


<section>

## Problem statement

* Short waves are modulated by ambient longer waves.
* Well studied but not fully understood; many processes going on.
* Modulation is important for at least:
  - Remote sensing (e.g. *EM return from Bragg waves carry information about long waves*)
  - Numerical wave prediction (e.g. *can different wave bands be treated independently in wind input functions?*)
  - _In situ_ measurements (e.g. *a fixed wave staff measures modulated waves.*)
</section>


<section>

## Dynamics of a linear wave

<img class="stretch" src="assets/wave_diagram.jpeg">
</section>


<section>

## One possible look at hydrodynamic modulation

* Linear wave theory takes us a long way.
* Early analytical solution by Longuet-Higgins & Stewart (1960):
  - Peak modulation at long-wave crests and proportional to $1 + \varepsilon_L$
* Numerical simulations by Peureux et al. (2021):
  - Short waves grow indefinitely due to convergence by long waves.
  - Sensitive to initial conditions--unstable if not initialized with L-H&S solution.
</section>


<section>

## This talk's science questions

* Do stable solutions exist for more realistic long-wave trains/groups?
* Are they different from L-H&S (1960) and Peureux et al. (2021) solutions and why?
* Should they be incorporated in spectral wave models beyond the cumulative MSS in dissipation (e.g. Romero, 2019)?
</section>