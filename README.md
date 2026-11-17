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


## Օգտագործված գրականություն

1. Самарский А. А., Гулин А. В., Численные методы, Москва, «Наука», 1989.
2. Бахвалов Н. С., Жидков Н. П., Кобельков Г. М., Численные методы, Москва, «БИНОМ. Лаборатория знаний», 2004.
3. Markowich P. A., Applied Partial Differential Equations: A Visual Approach, Berlin, Springer, 2007.

Օգտագործված բաժիններ՝ [1]՝ մաս III, գլ. 1 (§ 1–3, 6) և գլ. 2. [2]՝ գլ. 10 (§ 1, § 6). [3]՝ գլ. 5։
