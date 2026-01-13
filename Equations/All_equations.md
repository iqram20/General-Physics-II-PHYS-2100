# PHYS 2100 — Chapters 5 & 6
## Electric Charges, Fields, and Gauss’s Law

---

# Constants (SI Units)

$$
e = 1.602 \times 10^{-19}\ \text{C} \quad \text{(elementary charge)}
$$

$$
\varepsilon_0 = 8.85 \times 10^{-12}\ \text{C}^2/(\text{N·m}^2) \quad \text{(vacuum permittivity)}
$$

$$
k = \frac{1}{4\pi\varepsilon_0} = 8.99 \times 10^9\ \text{N·m}^2/\text{C}^2
$$

---

# Common Parameter Definitions

- \( q, q_1, q_2 \): point charges (C)
- \( Q \): total charge (C)
- \( Q_{\text{enc}} \): enclosed charge (C)
- \( n \): number of elementary charges
- \( r \): distance from charge or axis (m)
- \( R \): radius of sphere or cylinder (m)
- \( A \): area (m²)
- \( V \): volume (m³)
- \( L \): length (m)
- \( \lambda \): linear charge density (C/m)
- \( \sigma \): surface charge density (C/m²)
- \( \rho \): volume charge density (C/m³)
- \( \vec{E} \): electric field (N/C)
- \( \vec{F} \): electric force (N)
- \( \vec{A} \): area vector
- \( \theta \): angle between field and area or velocity
- \( m \): mass (kg)
- \( \vec{p} \): electric dipole moment
- \( \Phi_E \): electric flux (N·m²/C)

---

# Chapter 5 — Electric Charges and Fields

## Charge
$$
Q = ne
$$

---

## Coulomb’s Law
$$
F = k \frac{|q_1 q_2|}{r^2}
$$

$$
\vec{F}_{12} = k \frac{q_1 q_2}{r^2}\hat{r}
$$

---

## Superposition Principle
$$
\vec{F}_{\text{net}} = \sum_i \vec{F}_i
$$

$$
\vec{E}_{\text{net}} = \sum_i \vec{E}_i
$$

---

## Electric Field
$$
\vec{E} = \frac{\vec{F}}{q}
$$

$$
\vec{E} = k \frac{q}{r^2}\hat{r}
$$

---

## Electric Force in an Electric Field
$$
\vec{F} = q\vec{E}
$$

---

## Continuous Charge Distributions
$$
\lambda = \frac{Q}{L}
$$

$$
\sigma = \frac{Q}{A}
$$

$$
\rho = \frac{Q}{V}
$$

---

## Electric Fields from Symmetric Distributions

### Infinite Line Charge
$$
E = \frac{\lambda}{2\pi\varepsilon_0 r}
$$

### Infinite Sheet of Charge
$$
E = \frac{\sigma}{2\varepsilon_0}
$$

### Parallel Plates
$$
E = \frac{\sigma}{\varepsilon_0}
$$

---

## Electric Dipole
$$
\vec{p} = q\vec{d}
$$

$$
\tau = pE\sin\theta
$$

---

## Motion of Charged Particle
$$
\vec{F} = m\vec{a} = q\vec{E}
$$

$$
a = \frac{qE}{m}
$$

---

# Chapter 6 — Gauss’s Law

## Electric Flux
$$
\Phi_E = \vec{E}\cdot\vec{A} = EA\cos\theta
$$

$$
\Phi_E = \iint_S \vec{E}\cdot d\vec{A}
$$

---

## Gauss’s Law
$$
\oint_S \vec{E}\cdot d\vec{A} = \frac{Q_{\text{enc}}}{\varepsilon_0}
$$

---

## Conductors (Electrostatic Equilibrium)
$$
E_{\text{inside conductor}} = 0
$$

$$
E_{\text{just outside conductor}} = \frac{\sigma}{\varepsilon_0}
$$

---

## Spherical Charge Distributions

### Uniform Solid Sphere
$$
E = \frac{1}{4\pi\varepsilon_0}\frac{Qr}{R^3} \quad (r < R)
$$

$$
E = \frac{1}{4\pi\varepsilon_0}\frac{Q}{r^2} \quad (r \ge R)
$$

---

### Conducting Spherical Shell
$$
E = 0 \quad (r < R)
$$

$$
E = \frac{1}{4\pi\varepsilon_0}\frac{Q}{r^2} \quad (r \ge R)
$$

---

## Cylindrical Charge Distributions

### Uniform Solid Cylinder
$$
E = \frac{\rho r}{2\varepsilon_0} \quad (r < R)
$$

$$
E = \frac{\lambda}{2\pi\varepsilon_0 r} \quad (r \ge R)
$$

---

## Flux–Charge Relation
$$
Q_{\text{enc}} = \varepsilon_0 \Phi_E
$$
