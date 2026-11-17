# Numerical method for the Dirichlet problem for a nonlinear elliptic equation

Diploma work (written in Armenian), Yerevan 2026.

**Topic (hy):** Մի ոչ գծային էլիպսական հավասարման համար Դիրիխլեի խնդրի լուծման թվային մեթոդի մշակում և հետազոտում

The Dirichlet problem for a semilinear elliptic equation

```
Δu − q(x, u) = −f(x)   in a rectangle G,      u = μ   on the boundary Γ,      ∂q/∂u ≥ 0,
```

is reduced to a grid problem and solved numerically. The model nonlinearity is `q = a·sinh u`
(the equilibrium potential of a semiconductor, the mean-field equation). The linear Poisson problem
serves as the baseline, and its maximum principle is reused through linearization to prove
comparison, uniqueness and stability for the nonlinear problem.

## Files

| File | Content |
|---|---|
| `Diploma_Work.tex` | LaTeX source (single file, XeLaTeX) |
| `Diploma_Work.pdf` | compiled text |

## Status

| Section | Content | Status |
|---|---|---|
| 1 | Problem statement: Poisson problem, maximum principle, semilinear problem, linearization, comparison theorem, stability and uniqueness | done |
| 2 | Grid and five-point scheme, canonical and matrix form, second-order approximation | done |
| 3 | Grid problem: solvability, stability, convergence | planned |
| 4 | Solving the nonlinear grid system (Picard / Newton iteration) | planned |
| 5 | Numerical experiments | planned |

## Building the PDF

The text is Armenian, so it must be compiled with **XeLaTeX** (font Sylfaen if installed, otherwise DejaVu Serif).
Run it twice to get the table of contents and references:

```
xelatex Diploma_Work.tex
xelatex Diploma_Work.tex
```

## Sources

1. A. A. Samarskii, A. V. Gulin, *Numerical methods* (in Russian), Nauka, Moscow, 1989 - Part III, Ch. 1 and 2.
2. N. S. Bakhvalov, N. P. Zhidkov, G. M. Kobelkov, *Numerical methods* (in Russian), BINOM, Moscow, 2004 - Ch. 10 (sections 1 and 6), Ch. 7.
3. P. A. Markowich, *Applied Partial Differential Equations: A Visual Approach*, Springer, Berlin, 2007 - Ch. 5.

The books themselves are not part of this repository.
