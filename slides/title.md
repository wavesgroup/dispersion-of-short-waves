<section>

# Dispersion of short waves riding on longer waves

_Milan Curcic_


_Department of Ocean Science, University of Miami_

_Frost Insitute for Data Science & Computing, University of Miami_

_COMPASS Seminar Series, Rosenstiel School_

_May 1, 2024_
</section>


<section>

## Problem statement

* Short ocean waves are modulated by ambient longer waves.
* Well studied but not fully understood; many processes going on.
* Modulation is important for at least:
  - Remote sensing (e.g. *EM return from Bragg waves carry information about long waves*)
  - Numerical wave prediction (e.g. *can different wave bands be treated independently in wind input functions?*)
  - _in situ_ measurements (e.g. *a fixed wave staff measures modulated waves.*)
</section>


<section>

## Importance for remote sensing

TODO
</section>

<section>

## Importance for numerical wave prediction

* Numerical wave models solve the wave action balance equation.
* This equation includes empirical source and sink functions.
* Wave forecast models provide:
  - Critical information for marine operations and coastal communities
  - Surface boundary conditions for atmosphere and ocean circulation models
* State-of-the-art wave dissipation functions (e.g. Romero, 2019) parameterize
  this modulation effect through the cumulative mean square slope (MSS).
</section>


<section>

## Dynamics of a linear wave

<img class="stretch" src="assets/wave_diagram.jpeg">
</section>


<section>

## Importance for the interpretation of _in situ_ wave measurements

* Fixed sensor measures the modulated wave, not the intrinsic one.
* Measured short-wave energy ($k = 10\ rad/m$) will be "smeared" in wavenumber space in presence of longer waves.

<img class="stretch" src="assets/fig_modulation_effect_on_shortwave_spectra.png">
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