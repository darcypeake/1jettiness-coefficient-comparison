# 1-Jettiness Coefficient Comparison

Symbolic validation of ARES-formalism resummation coefficients against the SCET-derived N-jettiness subtraction coefficients, for the $N=1$ (1-jettiness, $\tau_1$) case relevant to $pp \to Z + \text{jet}$.

## Contents

- `h10_qqbar.nb` — Mathematica notebook validating the ARES $h_{10}$ coefficient against the $N$-jettiness counterpart $\mathcal{C}_{-1}^{(1)}$ for the $q\bar{q}$ channel, using the relation $\mathcal{C}_{-1}^{(1)} = 2h_{10}$.
- `h22-h21.nb` — Mathematica notebook computing and cross-checking the ARES $h_{21}$ and $h_{22}$ coefficients against their $N$-jettiness counterparts $\mathcal{C}_0^{(2)}$ and $\mathcal{C}_1^{(2)}$ respectively, using $\mathcal{C}_1^{(2)}/8 = h_{22}$ and $\mathcal{C}_0^{(2)}/(-4) = h_{21}$. This is done generally for any channel.

Comments throughout each notebook explain the steps taken to validate each coefficient.

## References

- J. Gaunt, M. Stahlhofen, F.J. Tackmann, J.R. Walsh, *N-jettiness Subtractions for NNLO QCD Calculations*, JHEP 09 (2015) 058, [arXiv:1505.04794](https://arxiv.org/abs/1505.04794)
