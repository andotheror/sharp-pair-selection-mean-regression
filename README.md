# Sharp Pair Selection for Mean Regression

## Abstract

Suppose a learner may train the empirical mean on two optimally selected examples, with repetition, and is evaluated by squared loss on the full dataset. How much worse can this be than the full mean? This is the first open column in a recent data-selection problem. We determine the exact answer in every dimension: 

$$F(d,2)=1+\max\left\\{\frac13,\frac{d-1}{2d}\right\\}.$$

 Thus the sharp factor is $4/3$ for $d\leq3$ and $(3d-1)/(2d)$ for $d\geq4$. The two branches reveal distinct obstructions. A rare point on a line forces the dimension-free term, while a uniform regular simplex forces the dimension term. The proof gives a stronger convex-geometric theorem for distributions on at most $m$ atoms. Its key step is an explicit antithetic distribution over pairs. If one atom has mass at least $1/4$, a star coupling has exactly one third of the original second moment. Otherwise, a complete-graph coupling has a closed-form second moment, and a single Jensen inequality proves that uniform weights are worst. A variance-minimizing Caratheodory reduction then transfers the result to arbitrary finite datasets. This resolves all cases with selection budget two, supplies a short proof of the previously isolated planar case, and separates variance-normalized data selection from radius-normalized approximate Caratheodory bounds.

## Keywords

data selection, mean estimation, squared loss, approximate Caratheodory, convex geometry, machine teaching, coresets

## Files

- `main.pdf`, `supplement.pdf`
- `main.tex`, `supplement.tex`
- `references.bib`
- `aistats2027.sty`, `fancyhdr.sty`
- `main.pdf.ots`, `supplement.pdf.ots`, `README.md.ots` OpenTimestamps priority proofs
