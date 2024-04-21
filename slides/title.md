<section>

# Dispersion of short waves riding on longer waves

_Milan Curcic_


_Department of Ocean Science, University of Miami_

_Frost Insitute for Data Science & Computing, University of Miami_

_WISE 2024_, Cargese, France
</section>


<section>

## Problem statement

* Short waves are modulated by ambient longer waves.
* True even in absence of wave growth or dissipation
* Well studied but not yet fully understood
* Important for:
  - Remote sensing (e.g. EM return from Bragg waves carry information about long waves)
  - Numerical wave prediction (e.g. can different wave bands be treated independently in wind input functions?)
</section>


<section>

## Problem statement (cont.)

* Linear wave theory takes us a long way.
* Early analytical solution by Longuet-Higgins & Stewart (1960):
  - Peak modulation at long-wave crests and proportional to $1 + a_L k_L$
* Numerical simulations by Peureux et al. (2021):
  - Short waves grow indefinitely due to resonance with wavenumber modulations.
  - Sensitive to initial conditions.
</section>


<section>

## This talk's science questions

* Do stable solutions exist for more realistic long-wave trains?
* Are they different from L-H&S (1960) and Peureux et al. (2021) solutions?
* Can they and should they be incorporated in spectral wave models?
</section>