# Q10 — Asymptotic $\mathfrak{su}(2)$-Isotropy of the Effective Quadratic Form

This repository contains the source of the **Q10 Cosmochrony paper**
[*Asymptotic $\mathfrak{su}(2)$-Isotropy of the Effective Quadratic Form*](out/q10.pdf).

Papers Q7–Q9 establish that the effective operator $L_{\mathrm{eff}}$ on
$\mathbb{R}_\tau \times \mathrm{Heis}_3(\mathbb{R})$ has principal symbol
$\sigma_2(L_{\mathrm{eff}})|_{H_{\mathrm{eff}}} = A_H(k_X^2+k_Y^2) + A_Z k_Z^2$ with
$A_Z = 2$ (Casimir eigenvalue on $\operatorname{Sym}^2(V_\rho)$, Q8). Identifying
$A_H = 2$ completes the effective metric to $g^{\mu\nu} = \mathrm{diag}(-A_\tau,2,2,2)$.

## Core Result

The paper proves $A_H \to 2$ from two structural inputs:

1. **Asymptotic character-independence** of the O-series spectral observables
   ($\sigma_c(n) \to \sigma_*(n)$ uniformly in $c$), from BI parity and the O25 campaign;
2. **Uniqueness** of the $\mathfrak{su}(2)$-invariant quadratic form on
   $\operatorname{Sym}^2(V_\rho)$ (Q7 Lemma 4.3).

Character-independence forces the effective form on $H_{\mathrm{eff}}$ to be scalar under
the $\mathfrak{su}(2)$ action, and the unique such form is the Casimir with value 2. The
result is conditional on the O-series universality (numerically confirmed for $q \le 211$)
and the bridge non-obstruction hypothesis of Q7–Q9.

## Keywords

su(2) isotropy, Casimir operator, effective metric, Heisenberg group, spectral
universality, symmetric square, emergent Lorentzian geometry.

## Repository Contents

```
q10/
├── tex/         # LaTeX sources (main + cosmochrony-bibliography.bib)
├── out/         # Compiled paper PDF (q10.pdf)
├── zenodo.json  # Zenodo deposition metadata
└── README.md
```

## Links

- 📄 [Paper PDF](out/q10.pdf)
- 🔗 DOI: [10.5281/zenodo.19880900](https://doi.org/10.5281/zenodo.19880900)
- 🌐 Website: https://cosmochrony.org/science/emergent-geometry/q10/

## Citation

> J. Beau, *Asymptotic $\mathfrak{su}(2)$-Isotropy of the Effective Quadratic Form*,
> Zenodo, 2026. DOI: 10.5281/zenodo.19880900.

## Acknowledgements

Portions of the editorial refinement benefited from iterative interactions with large
language models, used as analytical assistants. All claims and final formulations remain
the sole responsibility of the author.
