# Q10 — Toward Coefficient Isotropy from Character Uniformity

This repository contains the source of the **Q10 Cosmochrony paper**
*Toward Coefficient Isotropy from Character Uniformity: A Stability Lemma and Its Missing Geometric Inputs*.

An isotropic spatial geometry reconstructed from the admissible fibre would need the horizontal coefficient $A_H$
and the central coefficient $A_Z$ of a positive rank-three spatial form to agree, and would need their common value.
The paper isolates what uniformity of the O-series fingerprint observable across characters can contribute to that
question. The observable $\sigma_b(n) = \delta r_n(b)/|S_n|$ is a Gram–Schmidt rank increment per breadth-first shell.

## Core Result

- **Stability lemma (unconditional).** If data $x_{i,n}$ satisfy $|x_{i,n} - s(n)| \le \varepsilon\, s(n)$ with
  $s > 0$ and $\varepsilon < 1$, any two averages with a common depth weighting have a ratio within
  $2\varepsilon/(1-\varepsilon)$ of one; the bound is attained.
- **Conditional coefficient isotropy (Theorem 1.1).** Under the uniformity hypothesis [U], a sector assignment [W],
  a linear response law [R] and a supplied positive rank-three target [T],
  $|A_H/A_Z - 1| \le 2\varepsilon/(1-\varepsilon)$. The absolute value follows only from an independently supplied
  scale [S]. None of [U], [W], [R], [T], [S] is established.
- **Invariance fixes no coefficient.** Invariant Hermitian forms on the spin-one module form one ray; the Casimir
  acts as $2$, but this singles out a normalisation, not a coefficient.
- **Exact conjugation parity** holds for conjugately matched fingerprint data with an identical normalisation. The
  O25 campaign samples its paired blocks independently and does not meet this condition.
- **The inputs cited for [U] do not imply it.** Parity, a three-dimensional neutral sector, rank stability and
  concentrated pair exponents are compatible with the failure of [U] for every $\varepsilon < 1/3$.
- The Q7 compression entries $2 + 4\sin^2(\pi k/q)$ are Rayleigh-quotient identities of the discrete Weil
  Laplacian, not metric coefficients. No coefficient value is derived.

## Keywords

Heisenberg group, Weil representation, spectral universality, Gram–Schmidt rank increment, complex conjugation,
su(2)-invariant forms, Schur's lemma, coefficient isotropy, emergent geometry.

## Repository Contents

```
q10/
├── tex/         # LaTeX sources (main + cosmochrony-bibliography.bib)
├── compile.sh   # Build script (output in out/, not versioned)
├── zenodo.json  # Zenodo deposition metadata
└── README.md
```

## Links

- 🔗 DOI: [10.5281/zenodo.19880900](https://doi.org/10.5281/zenodo.19880900)
- 🌐 Website: https://cosmochrony.org/science/emergent-geometry/q10/

## Citation

> J. Beau, *Toward Coefficient Isotropy from Character Uniformity: A Stability Lemma and Its Missing Geometric
> Inputs*, Zenodo, 2026. DOI: 10.5281/zenodo.19880900.

## Acknowledgements

Portions of the analysis and editorial development benefited from iterative interactions with large language
models used as analytical assistants. All mathematical claims and interpretations remain the author's
responsibility.
