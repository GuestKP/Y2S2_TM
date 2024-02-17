# Homework 3 Report
Kuklin Pavel, B22-RO-01

### Tools
Google Colab, Python (manim, numpy, sympy, matplotlib libraries); Github, Markdown.

## Task 1

### Task description
![](/HW3/task1_description.png)

### Task explanation

**Body D is in translatry motion**: $\vec{O_1A} = \vec{O_2B}$ (they have same magnitude $R$ and angle $\phi$), then $\vec{AB} = - \vec{O_1A} + \vec{O_1O_2} + \vec{O_2B} = \vec{O_1O_2} = const$.

Therefore, $\omega_D = 0$, $\vec{v^{tr}_M} = \vec{v_A}$ and $\vec{a^{tr}_M} = \vec{a_A}$.

**Absolute velocity of M:**

$\omega(t) = \frac{d}{dt}\phi(t) = \frac{1}{12}\pi t$.

$v_A = R\omega(t)$. Substituting values, we **get** $v_A = 2.5\pi$. Direction is shown on picture.

$v^{rel}_M(t) = \frac{d}{dt}s_r(t) = 6t^2 + 3$. Substituting values, we **get** $v^{rel}_M = 27$. Direction is shown on picture.

The angle between $\vec{v^{tr}_M}$ and $x$ axis is $\alpha = \phi(t) + \frac{\pi}{2}$. Substituting $t_1$, we get $\alpha = \frac{2}{3}\pi$. Also, $\phi(t_1) = \frac{1}{6}\pi$

Then absolute velocity of M is

$$v_M = |\vec{v^{tr}_M} + \vec{v^{rel}_M}| = \sqrt{(-v^{rel}_M + v^{tr}_Mcos\alpha)^2 + (v^{tr}_Msin\alpha)^2} \approx 31.67$$

**Coriolis acceleration:** as body D does not rotate ($\omega_D = 0$), there is no coriolis acceleration ($\vec{a^{cor}} = 2\vec{\omega_D} \times \vec{v^{rel}} = 0$).

**Absolute acceleration of M:**

$\epsilon(t) = \frac{d}{dt}\omega(t) = \frac{\pi}{12}$.

$\vec{a_A} = \vec{a^\tau_A} + \vec{a^n_A}; \ \ \vec{a^\tau_A} = R\epsilon(t_1) \approx 3.93$ and $\vec{a^n_A} = R\omega(t_1)^2 \approx 4.11$.

$a^{rel}_M(t) = \frac{d}{dt}v^{rel}_M(t) = 12t$. Substituting values, we **get** $a^{rel}_M = 24$.

Then absolute acceleration of M is $\vec{a_M} = \vec{a^{rel}_M} + \vec{a^\tau_A} + \vec{a^n_A}$. Let

$a_{Mx} = -a^{rel}_M + a^\tau_Acos\alpha - a^n_Acos\phi \approx -29.5244$

$a_{My} = a^\tau_Asin\alpha - a^n_Asin\phi \approx 1.3485$

Then

$$ a_M = \sqrt{a_{Mx}^2 + a_{My}^2} \approx 29.56$$

### Answer

Absolute velocity of M is $31.67$, coriolis acceleration of M is 0, absolute acceleration of M is $29.56$.

## Task 2

### Task description
![](/HW3/task2_description.png)

### [Simulation link](https://colab.research.google.com/drive/1VfeQQUSoH-hjsXze-pNiW3Emmm00yzDL?usp=sharing)
Note: vectors are scaled by different factors.

### Task explanation

no way

### Plots
![](/HW3/task2_plots.png)

### Simulation screenshots
![](/HW3/task2_ss.png)