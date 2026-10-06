# An Aggregate CM-Pair Estimate and a 5/3 Bound for Valuation Products of abc Triples

Ruiyi Zhang

For pairwise coprime positive integers with `a + b = c`, write `R = rad(abc)` and
`P(abc) = prod_{p | abc} v_p(abc)`. The manuscript proves

    P(abc), d(abc) <<_eps R^{5/3+eps},

where `d` is the divisor function. The first step is an aggregate fixed-radius
estimate for CM points on an indefinite Shimura curve: for CM discriminants in
`[Delta, 2*Delta]`, the number of nearby ordered pairs is

    #{(P,Q) in P_Delta^2 : d(P,Q) <= r_0} << |P_Delta| + Delta*(1 + Delta^2/N)*N^eps,

uniformly in all polynomial ranges `Delta <= N^A`. It is established from the
published local-density formulas together with the characteristic-matrix framework
of Bruinier, Li and Möller. A spatial Cauchy-Schwarz then bounds the first absolute
moment of the CM-packet, and AM-GM applied to the logarithmic average in Pasten's
Arakelov estimate completes the argument; neither a fourth moment nor a pointwise
subconvexity estimate is required.

## Contents

- `aggregate-cm-pair-abc.tex` - LaTeX source (amsart).
- `aggregate-cm-pair-abc.bbl` - frozen bibliography; no BibTeX run is needed.
- `aggregate-cm-pair-abc.pdf` - compiled manuscript, 17 pages.
- `SHA256SUMS` - checksums of the files above.

The source is the two-file payload frozen on 2026-08-21 and uploaded to arXiv on
2026-08-22 as submission `submit/7979306`; the paper carries no arXiv identifier.

## Build

    pdflatex aggregate-cm-pair-abc.tex
    pdflatex aggregate-cm-pair-abc.tex

Verified with pdfTeX 1.40.25 (TeX Live 2023): exit 0, no undefined citation or
reference, 17 pages.
