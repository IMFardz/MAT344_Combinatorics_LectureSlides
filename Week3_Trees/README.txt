TREES — SECTION 1.3
74 Beamer slides for Harris, Hirst and Mossinghoff, Combinatorics and Graph Theory, 2nd edition.

CONTENTS
- week3_trees.pdf: compiled slides
- week3_trees.tex: editable Beamer source
- png/slide-01.png through slide-74.png: slide images

COMPILATION
Run twice:
  pdflatex week3_trees.tex
Requires a standard TeX distribution with Beamer, TikZ/PGF, AMS packages and booktabs.
Keep all figure_*.png files beside week3_trees.tex when compiling. Other graphs are drawn in TikZ.

STYLE
Uses the previous Distance in Graphs deck's preamble: 16:9, 11pt, Madrid theme,
blue title bars, boxed definitions/theorems, frame numbers, and Jeremy Quastel as author.

COVERAGE
1–9: Definitions, small trees, and applications.
10–26: Properties, Theorems 1.10–1.16 and proofs.
27–42: Spanning trees, Kruskal's algorithm, its proof, and Prim's algorithm.
43–56: Labeled trees, Cayley's formula, and Prüfer encoding/decoding.
57–72: Matrix Tree Theorem: definitions, theorem, expanded proof, and textbook example.
60–69: Alternative proof: roadmap, signed incidence matrix, root deletion, Cauchy–Binet, leaf-removal induction, disconnected case, and equality of cofactors.
73–74: Summary and Next time: Trails, Circuits, Paths and Cycles.

The theorem numbering follows the textbook. Explanations are written for slides.
Figures 1.31–1.35, Figure 1.41, the spanning-tree examples, the railroad Kruskal figure, and the figures for the proofs of Theorems 1.14 and 1.16 are user-supplied textbook images. Other diagrams are newly drawn; the six-town weighted example is an original example.
The Prüfer example and four-vertex matrix example follow the textbook's mathematical data.
The matrix proof explicitly uses squared minors in Cauchy–Binet and distinguishes
reduced determinants from the zero determinant of the full Laplacian.
This complete section is likely best spread across more than one lecture.

SEPARATE ALTERNATIVE VERSION
The original 71-slide deck is preserved unchanged. Only its seven Matrix Tree proof slides were replaced with ten more explicit proof slides. Cauchy–Binet is stated and used as a linear algebra fact.
