# Brezis–Gallouet leading constant on the 2D torus

## Description of constant

Let $\mathbb T^2 = (\mathbb R / 2\pi\mathbb Z)^2$ and let $u \in H^2(\mathbb T^2)$ with zero mean
$\int_{\mathbb T^2} u(x)\,dx = 0$.  Define
$$
\delta(u) := \frac{\|\Delta u\|_{L^2(\mathbb T^2)}^2}{\|\nabla u\|_{L^2(\mathbb T^2)}^2}.
$$

Define the *one-log Brezis–Gallouet leading constant* $C_{\mathrm{BG}}^{(1\log)}(\mathbb T^2)$ as the infimum
of $C>0$ such that there exists a finite $K$ with
$$
\|u\|_{L^\infty(\mathbb T^2)}^2 \le C\,\|\nabla u\|_{L^2(\mathbb T^2)}^2 \bigl(\ln \delta(u) + K\bigr)
\qquad\text{for all such }u.
$$

This constant controls the sharp coefficient in the logarithmic critical embedding underlying
standard Brezis–Gallouet-type estimates used in 2D PDE (including Navier–Stokes attractor and
regularity arguments).

## Known upper bounds

| Bound | Reference | Comments |
|---|---|---|
| $C_{\mathrm{BG}}^{(1\log)}(\mathbb T^2) \le \dfrac{e}{4\pi}$ | [BG2011] | Explicit classical one-log inequality with computed constants |

## Known lower bounds

| Bound | Reference | Comments |
|---|---|---|
| $C_{\mathrm{BG}}^{(1\log)}(\mathbb T^2) \ge \dfrac{1}{4\pi}$ | [BG2011] | Sharp torus asymptotics via variational formulation |

## Additional comments

A sharper *log+loglog* form is known on $\mathbb T^2$ via a constrained variational problem:
for $\delta(u)>0$,
$$
\|u\|_{L^\infty(\mathbb T^2)}^2 \le \frac{1}{4\pi}\,\|\nabla u\|_{L^2(\mathbb T^2)}^2
\Bigl[\ln\delta(u) + \ln(1+\ln\delta(u)) + L\Bigr],
$$
with $L \approx 2.15$ in the cited formulation.  This is described as the sharp estimate
for the Brezis–Gallouet inequality on the torus.

Thus, the remaining "optimization" tension is largely about the *best possible remainder structure*
(one-log vs log+loglog), not the leading coefficient in the sharp torus asymptotics.

## References

- [BG1980] Brezis, H.; Gallouet, T. *Nonlinear Schrödinger evolution equations.* Nonlinear Anal. 4 (1980), 677–681.
- [BG2011] Bartuccelli, M. V.; Gibbon, J. D. *Sharp constants in the Sobolev embedding theorem.* J. Math. Phys. 52 (2011), 093706.
- [BDZ2010] Bartuccelli, M. V.; Deane, J. H. B.; Zelik, S. *Asymptotic expansions and extremals for the critical Sobolev and Gagliardo–Nirenberg inequalities on a torus.* arXiv:1012.2061.

## Contribution notes

This entry was prepared with LLM assistance (Claude) for literature synthesis and formatting.
