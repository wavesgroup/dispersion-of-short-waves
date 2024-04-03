<section>

# Governing equations
</section>


<section>

## Governing equations for short waves

* Dispersion in deep water with ambient currents:

$$
\omega = \sqrt{g k} + k U
$$

* Conservation of wave crests:

$$
\dfrac{\partial k}{\partial t} + \dfrac{\partial \omega}{\partial x} = 0
$$

* Conservation of wave action:

$$
\dfrac{\partial N}{\partial t} + \dfrac{\partial \left[\left(C_g + U\right) N\right]}{\partial x} = 0
$$
</section>


<section>

## Governing equations for long waves

* Sine waves with amplitude $a_L$ and steepness $\varepsilon_L$:
$$
\eta = a_L \cos\psi
$$

$$
U = a_L \omega_L e^{\varepsilon_L \cos\psi} \cos\psi
$$

$$
W = a_L \omega_L e^{\varepsilon_L \cos\psi} \sin\psi
$$
</section>


<section>

## Governing equations, expanded

* Prognostic equation for wavenumber:
$$
\dfrac{\partial k}{ \partial t} + 
(C_g + U) \dfrac{\partial k}{\partial x} + 
\dfrac{1}{2} \sqrt{\dfrac{k}{g}} \dfrac{\partial g}{\partial x} + 
k \dfrac{\partial U}{\partial x} = 
0
$$
* Prognostic equation for wave action:
$$
\dfrac{\partial N}{ \partial t} +
(C_g + U) \dfrac{\partial N}{\partial x} +
N \dfrac{\partial C_g}{\partial x} + 
N \dfrac{\partial U}{\partial x} =
0
$$
</section>