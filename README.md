# An Aggregate CM-Pair Estimate and a 5/3 Bound for Valuation Products of abc Triples

Ruiyi Zhang

For pairwise coprime positive integers with `a + b = c`, write `R = rad(abc)` and
`P(abc) = prod_{p | abc} v_p(abc)`. The manuscript proves

    P(abc), d(abc) <<_eps R^{5/3+eps},

where `d` is the divisor function. The first step is an aggregate fixed-radius
estimate for CM points on an indefinite Shimura curve: for CM discriminants in
`[Delta, 2*Delta]`, the number of nearby ordered pairs is

    #{(P,Q) in P_Delta^2 : d(P,Q) <= r_0} << |P_Delta| + Delta*(1 + Delta^2/N)*N^eps,

uniformly in all polynomial ranges `Delta <= N^A`. It is established by an elementary
local orbit count in the Bruhat-Tits tree, using the characteristic-matrix framework
of Bruinier, Li and Möller. A spatial Cauchy-Schwarz then bounds the first absolute
moment of the CM-packet, and AM-GM applied to the logarithmic average in Pasten's
Arakelov estimate completes the argument; neither a fourth moment nor a pointwise
subconvexity estimate is required.

## Contents

- `aggregate-cm-pair-abc.tex` - LaTeX source (amsart).
- `aggregate-cm-pair-abc.bbl` - frozen bibliography; no BibTeX run is needed.
- `aggregate-cm-pair-abc.pdf` - compiled manuscript, 18 pages.
- `SHA256SUMS` - checksums of the files above.

## Versions

- Release `v2` (current, source frozen 2026-08-25): the local orbit bound of Section 3
  is proved directly from the local structure of quaternion orders and the
  Bruhat-Tits tree, so the argument no longer passes through the local-density
  formulas used earlier; the positivity of the integer `m = (b^2 - de)/N^flat` in the
  nonsingular pair case is proved by a reverse Cauchy-Schwarz inequality on the
  negative cone of the signature `(2,1)` form; the bibliography is regenerated and
  complete.
- Release `v1` (source frozen 2026-08-21): the earlier text, whose Section 3 obtained
  the same local factors from the published local-density formulas. Its source is
  byte-identical to the arXiv submission payload `submit/7979306` of 2026-08-22 and is
  kept as a provenance record.

The theorem statements and the exponent `5/3` are the same in both.

## Build

    pdflatex aggregate-cm-pair-abc.tex
    pdflatex aggregate-cm-pair-abc.tex
    pdflatex aggregate-cm-pair-abc.tex

Verified with pdfTeX 1.40.25 (TeX Live 2023): exit 0, no undefined citation or
reference, 18 pages.
