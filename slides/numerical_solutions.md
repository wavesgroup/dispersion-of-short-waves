<section>

# Numerical solutions
</section>


<section>

## Model setup

* Equations to solve:
$$
\dfrac{\partial k}{\partial t} = - \dfrac{\partial \omega}{\partial x}
$$
$$
\dfrac{\partial N}{\partial t} =  - \dfrac{\partial \left[\left(C_g + U\right) N\right]}{\partial x}
$$
* Numerical schemes:
  - Space differencing: 2$^{nd}$ order centered
  - Time integration: 4$^{th}$ order Runge-Kutta
  - 100 grid points in phase with periodic boundary conditions
</section>


<section>

## Initial conditions

* TODO
* Very important
* Discuss Peureux et al. (2021) findings
</section>


<section>

## Modulation over time: Infinite wave train

<img class="r-stretch" src="assets/fig_modulation_3panel_infinite_wave_train.png">
</section>


<section>

## Modulation over time: Linear ramp

<img class="r-stretch" src="assets/fig_modulation_3panel_linear_ramp.png">
</section>


<section>

## Modulation over time: Wave group

<img class="r-stretch" src="assets/fig_modulation_3panel_wave_group.png">
</section>


<section>

## What processes grow/decay the modulation? Infinite wave train

<img class="r-stretch" src="assets/fig_tendency_contributions_infinite_wave_train.png">
</section>


<section>

## What processes grow/decay the modulation? Linear ramp

<img class="r-stretch" src="assets/fig_tendency_contributions_linear_ramp.png">
</section>


<section>

## What processes grow/decay the modulation? Wave group

<img class="r-stretch" src="assets/fig_tendency_contributions_wave_group.png">
</section>


<section>

## Short wave modulation, revisited

<img class="r-stretch" src="assets/fig_wavenumber_modulation_by_ak_numerical.png">
</section>
