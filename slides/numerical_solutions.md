<section>

# Numerical solutions
</section>


<section>

## Model setup

* Essentially following Peureux et al. (2021)
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
  - $k_L = 1$, $k_s = 10$, $\varepsilon_L = 0.1$
</section>


<section>

## Initial conditions

* Initial conditions seem to be very important
* Peureux et al. (2021) found:
  - Stable solution if initialized with the L-H&S solution for $\widetilde k$
  - Unstable growth if initialized uniformly
  - _"...sudden appearance of a long wave perturbation in the middle of a homogeneous
short wave field."_
</section>


<section>

## Wave action and wavenumber evolution: Infinite wave train

<video
  width=600
  controls
  loop
  src="assets/modulation_movie_infinite_train.mp4"
  type="video/mp4">
</video>
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

## What if we emulate a "wave group"?

<img class="r-stretch" src="assets/fig_wave_group.png">
</section>


<section>

## Modulation over time: Wave group

<img class="r-stretch" src="assets/fig_modulation_3panel_wave_group.png">
</section>


<section>

## Wave action and wavenumber evolution: Wave group

<video
  width=600
  controls
  loop
  src="assets/modulation_movie_groups.mp4"
  type="video/mp4">
</video>
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

## New solutions compared to Longuet-Higgins & Stewart (1960)

<img width="450" src="assets/fig_wavenumber_modulation_by_ak_numerical.png">
<img width="450" src="assets/fig_wavenumber_modulation_relative_increase.png">
</section>


<section>

## Modulation of wind input to short waves

Evaluate relative change in $\left(\dfrac{u_*}{C_p}\right)^2$ due to the long waves:

<img class="r-stretch" src="assets/fig_wind_input_modulation.png">
</section>