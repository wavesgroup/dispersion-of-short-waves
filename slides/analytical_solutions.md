<section>

# Analytical solutions
</section>


<section>

## Analytical solution for wavenumber

* An analytical solution requires dropping terms from the wavenumber balance equation:
$$
\dfrac{\partial k}{ \partial t} + 
\cancel{(C_g + U) \dfrac{\partial k}{\partial x}} + 
\cancel{\dfrac{1}{2} \sqrt{\dfrac{k}{g}} \dfrac{\partial g}{\partial x}} + 
k \dfrac{\partial U}{\partial x} = 
0
$$
$$
\dfrac{\partial k}{ \partial t} = - k \dfrac{\partial U}{\partial x}
$$
</section>


<section>

## Short wave wavenumber

* Longuet-Higgins & Stewart (1960):
$$
\tilde{k} = k (1 + \varepsilon_L \cos\psi)
$$
* This study:
$$
\tilde{k} = k\ e^{\varepsilon_L \cos\psi e^{\varepsilon_L \cos\psi}}
$$
* This solution reduces to L-H&S if we Taylor-expand it and keep the 1$^{st}$ order term in $\varepsilon_L$.
</section>


<section>

## Short wave wavenumber (cont.)

<img class="r-stretch" src="assets/fig_wavenumber_modulation_by_phase.png">
</section>


<section>

## Short wave wavenumber (cont.)

<img class="r-stretch" src="assets/fig_wavenumber_modulation_by_ak.png">
</section>


<section>

## Short wave gravity

* Short waves are riding in the reference frame of the long wave surface so
  they accelerate downward on crests and upward on troughs.

$$
\tilde{g} = g \left[
    1 - \varepsilon_L e^{\varepsilon \cos\psi}
    \left( \cos\psi + \varepsilon_L \sin^2\psi \right)
\right]
$$

* On average, the mean gravity of short waves is reduced in presence of longer waves.
</section>


<section>

## Short wave gravity (cont.)

<img class="r-stretch" src="assets/fig_gravity_modulation_by_phase.png">
</section>


<section>

## Short wave gravity (cont.)

<img class="r-stretch" src="assets/fig_gravity_modulation_by_ak.png">
</section>