# Introduction to Causality & Causal Inference

A comprehensive, self-paced curriculum covering modern causal inference, structural causal models (SCMs), potential outcomes (Rubin causal model), quasi-experimental identification, causal machine learning, and causal discovery.

Delivered as a zero-dependency, single-file interactive application (`index.html`) featuring native HTML/Unicode mathematical formatting (no broken LaTeX rendering), executable Python and R snippets, landmark scientific papers, and conceptual mastery quizzes.

## Course Structure & Contents

| # | Module | Core Theoretical Focus | Landmark Methodological Papers |
|---|--------|------------------------|--------------------------------|
| 1 | The Causal Ladder & Foundations | Pearl's 3-Level Hierarchy, Simpson's Paradox, Fundamental Problem of Causal Inference | Pearl (2019), Simpson (1951) |
| 2 | Structural Causal Models & DAGs | Non-parametric SCMs, d-separation, chains, forks, colliders, Berkson's bias | Pearl (1988), Pearl (1995) |
| 3 | Potential Outcomes (Rubin Model) | ATE/ATT, SUTVA, Unconfoundedness (Ignorability), Positivity (Overlap) | Rubin (1974), Neyman (1923) |
| 4 | Identification: Backdoor, Frontdoor & Do-Calculus | Backdoor criterion, Frontdoor formula, Do-calculus completeness | Tian & Pearl (2002), Shpitser & Pearl (2006) |
| 5 | Propensity Scores, Matching & Weighting | Balancing property, IPW, Caliper matching, Doubly Robust (AIPW) estimation | Rosenbaum & Rubin (1983), Robins, Rotnitzky & Zhao (1994) |
| 6 | Quasi-Experiments (IV, DiD, RDD) | 2SLS, LATE theorem, Staggered DiD & Parallel Trends, Sharp/Fuzzy RDD | Imbens & Angrist (1994), Card & Krueger (1994), Callaway & Sant'Anna (2021) |
| 7 | Causal Machine Learning | CATE, Double/Debiased Machine Learning (DML), Neyman Orthogonality, Causal Forests | Chernozhukov et al. (2018), Wager & Athey (2018), Künzel et al. (2019) |
| 8 | Causal Discovery & Frontier Challenges | Constraint-based PC algorithm, GES, Additive Noise Models (ANM), Causal Representation Learning | Spirtes, Glymour & Scheines (1993), Kalisch et al. (2012), Peters et al. (2017), Schölkopf et al. (2021) |

## Key Features

1. **Robust Native Math Rendering**: Formulated using semantic HTML elements, Unicode symbols, and styled code cards rather than dynamic LaTeX engines, guaranteeing that equations render reliably across all browsers and offline environments without broken delimiters.
2. **Featured Landmark Literature**: Every module contains curated citations to foundational papers that defined the field, complete with external links (open-access where available), context notes, and summaries of why they mattered.
3. **Dual-Language Code Examples**: Python (`DoWhy`, `EconML`, `NetworkX`, `Scikit-Learn`) and R (`dagitty`, `grf`, `fixest`, `pcalg`, `WeightIt`) implementations demonstrate how theoretical formulas translate into production scripts.
4. **Interactive Concept Checks**: Every module concludes with multiple-choice self-assessments providing immediate feedback and explanations.
5. **Private Progress Tracking**: Progress is saved automatically using browser `localStorage`. No accounts, tracking scripts, external assets, or build tools are involved.

## How to Run

1. Download or clone `index.html`.
2. Double-click the file to open it in any modern browser (Chrome, Firefox, Safari, Edge).
3. (Optional) To host for students or colleagues, upload `index.html` to any static site platform, such as GitHub Pages, Netlify, or Cloudflare Pages.

## Contributing

Suggestions for additional landmark literature, clarified mathematical explanations, or new empirical code examples are welcome via pull requests or issue submissions.

## Acknowledgments

- Foundational Frameworks & Theories:
  - Judea Pearl (University of California, Los Angeles) for Directed Acyclic Graphs, d-separation, and do-calculus.
  - Donald B. Rubin (Harvard University) and Jerzy Neyman for the Potential Outcomes framework.
  - Joshua Angrist (MIT) and Guido Imbens (Stanford University) for Local Average Treatment Effect (LATE) econometrics.
  - James M. Robins (Harvard T.H. Chan School of Public Health) for semiparametric inference and double robustness.
  - Victor Chernozhukov (MIT) for Double/Debiased Machine Learning.
  - Susan Athey (Stanford) and Stefan Wager (Stanford) for Causal Forests and algorithmic policy learning.
  - Peter Spirtes, Clark Glymour, Richard Scheines (CMU), and Bernhard Schölkopf (MPI for Intelligent Systems) for causal discovery and representation learning.
- Pedagogical References & Textbooks:
  - *Causal Inference: What If* by Miguel A. Hernán and James M. Robins (Harvard University).
  - *Causal Inference: The Mixtape* by Scott Cunningham (Baylor University).
  - *Causal Inference for Statistics, Social, and Biomedical Sciences* by Guido W. Imbens and Donald B. Rubin.
  - *Elements of Causal Inference: Foundations and Learning Algorithms* by Jonas Peters, Dominik Janzing, and Bernhard Schölkopf (MIT Press).
  - *Mostly Harmless Econometrics* by Joshua D. Angrist and Jörn-Steffen Pischke.
  - Brady Neal's open lecture series *Introduction to Causal Inference*.
- Instructional design, software development, and documentation assistance: Gemini (Google).

## License

This project is licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).