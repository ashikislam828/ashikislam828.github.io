# Website Writing — Asikul Islam
Inspired by the section order and concise academic tone of Kamrun Nahar Keya’s website.


---

# Home

I am a Ph.D. student in Mathematics at the University of Houston, working at the intersection of numerical partial differential equations, reduced-order modeling, optimization, and scientific computing. My research focuses on developing efficient and reliable computational methods for large-scale, parameter-dependent systems, with applications to brain tumor growth modeling.

My current work includes tensor-based low-rank surrogate models, PDE-constrained parameter estimation, and the correction of reduced-model error in inverse problems. I am particularly interested in computational methods that accelerate repeated PDE simulations while preserving the mathematical consistency needed for optimization and inference.

Alongside my research, I serve as a Lead Teaching Assistant in Statistics for the Sciences at the University of Houston. I previously taught undergraduate mathematics as a Lecturer at the Canadian University of Bangladesh and Northern University of Bangladesh.

## News

- **2026:** Presented *Fast Tensorial Surrogate Models for Parametric Brain Tumor Growth Dynamics in Many-Query Regimes* at the SIAM Annual Meeting in Cleveland, Ohio.
- **2026:** Our preprint, *Tensorial Reduced-Order Models for Parametric Coupled Reaction-Diffusion Systems: Application to Brain Tumor Growth Modeling*, is [available on arXiv](https://arxiv.org/abs/2603.14101) and under review.
- **2025:** Received the Best Poster Award at the SIAM Texas–Louisiana Sectional Meeting, University of Texas at Austin.
- **2026:** Participated in the Bayesian Inverse Problems and Uncertainty Quantification Workshop at ICERM, Brown University.

---

# Bio

I am a doctoral researcher in the Department of Mathematics at the University of Houston, advised by Professor Andreas Mang. My dissertation, *Tensorial Reduced-Order Models for Parameter Estimation in Brain Tumor Growth Models*, develops numerical and optimization methods for computationally demanding nonlinear PDE systems. I expect to complete my Ph.D. in May 2027.

My research combines mathematical modeling, low-rank matrix and tensor methods, numerical optimization, and high-performance scientific computing. I develop fast forward models and derivative-consistent inverse methods, with an emphasis on making expensive simulations practical for parameter estimation and uncertainty analysis.

## Education

- **Ph.D. in Mathematics**, University of Houston, expected May 2027. Advisor: Professor Andreas Mang.
- **M.S. in Applied Mathematics**, University of Houston, Fall 2025.
- **M.S. in Mathematics**, University of Dhaka, December 2017.
- **B.S. in Mathematics**, University of Dhaka, August 2015.

## Academic Appointments

- **Graduate Teaching Assistant**, University of Houston (August 2022–present).
- **Graduate Research Assistant**, University of Houston (August 2024–July 2026), supported by NSF DMS-2145845.
- **Lecturer**, Northern University of Bangladesh (January–July 2022).
- **Lecturer**, Canadian University of Bangladesh (January 2018–December 2021).

## Research Interests

- Numerical partial differential equations and scientific computing
- Reduced-order modeling and low-rank tensor approximation
- PDE-constrained optimization and inverse problems
- Uncertainty quantification and scientific machine learning
- High-performance simulation of nonlinear parametric systems

[Download my full CV (PDF)](cv.pdf).

---

# Research

My research lies at the intersection of computational mathematics, numerical partial differential equations, low-rank tensor methods, and PDE-constrained optimization. I develop efficient algorithms for nonlinear parametric models that must be evaluated repeatedly in simulation, parameter estimation, and uncertainty analysis. Brain tumor growth modeling provides a central application of this work.

## Current Research

### Tensorial Reduced-Order Modeling for Parametric PDEs

I develop tensorial reduced-order models for nonlinear reaction–diffusion systems, from scalar tumor-growth equations to a six-species, nine-parameter model. My work uses higher-order singular value decomposition (HOSVD/Tucker) and Tensor Train representations, together with intrusive and non-intrusive reduced formulations. Spatial pre-compression, randomized linear algebra, and memory-efficient snapshot processing enable large-scale offline construction. Our numerical studies demonstrate online speedups of approximately 85–120 times over the corresponding full-order simulations.

### PDE-Constrained Optimization and Parameter Estimation

I study the recovery of unknown model parameters from observations of tumor evolution. Using a discretize-then-optimize approach, I derive sensitivities, discrete adjoints, gradients, and second-order information that are consistent with the fully discrete forward solver. For the multi-species problem, the numerical framework combines finite-volume discretization with Strang splitting, Crank–Nicolson diffusion steps, and Runge–Kutta reaction integration. I investigate Gauss–Newton, Newton-type, and constrained optimization methods, including regularization and discrepancy-based parameter selection.

### Derivative-Consistent Reduced-Order Inversion

I am developing an inverse framework in which parameter-dependent Tucker reduced bases are differentiated consistently with the reduced forward map. This requires accounting for the parameter dependence of the reduced basis, projected operators, and initial conditions, rather than differentiating only the reduced state variables. The goal is to obtain fast reduced sensitivities and reliable Gauss–Newton parameter estimates while preserving a transparent connection to the high-fidelity model.

### Correcting Reduced-Model Error in Inverse Problems

In collaborative work with Pegah Amiri and Andreas Mang, I investigate how approximation error in a reduced forward model affects the parameters recovered by an inverse solver. We use hyper-differential sensitivity analysis and post-optimality correction to estimate the change in an optimum caused by the difference between reduced- and full-order models. This approach aims to improve parameter accuracy with only a small number of additional full-order evaluations.

## Previous Research

My earlier work includes applications of fuzzy logic to forecasting and decision-making under uncertainty, as well as comparative studies of shortest-path algorithms.

## Future Interests

I am interested in extending derivative-consistent model reduction to uncertainty quantification and statistical inference; developing adaptive tensor approximation and sampling methods; and combining physics-based numerical models with scientific machine learning. A long-term goal is to build scalable, error-aware computational workflows for inverse problems and patient-specific biomedical modeling.

[Read my research statement (PDF)](research_statement.pdf).

---

# Teaching

My teaching emphasizes conceptual understanding, structured problem solving, and connections between mathematical theory, computation, and applications. I encourage students to explain their reasoning, interpret results, and develop the confidence to approach unfamiliar mathematical problems independently.

## University of Houston

**Graduate Teaching Assistant** | August 2022–present

### Lead Teaching Assistant — Statistics for the Sciences (MATH 3339)

- Coordinate teaching assistants and support course organization.
- Prepare homework solutions and assist with grading coordination for examinations.
- Conduct office hours, review sessions, and individual or group tutoring.

## Northern University of Bangladesh

**Lecturer** | January 2022–July 2022

### Undergraduate Courses Taught

- Statistics
- Calculus I and II

## Canadian University of Bangladesh

**Lecturer** | January 2018–December 2021

### Undergraduate Courses Taught

- Differential and Integral Calculus
- Probability and Statistics
- Fourier and Laplace Transforms
- Numerical Analysis
- Engineering Mathematics
- Complex Variables

## Teaching Approach

I introduce mathematical ideas through intuition and examples before developing formal definitions and methods. My instructional experience across different student backgrounds has reinforced the value of clear explanations, regular feedback, and carefully designed assessments. When appropriate, I incorporate computation and numerical examples to connect abstract ideas to practical applications.

[Read my teaching statement (PDF)](teaching_statement.pdf).

---

# Publications

A current publication list is also available through my [Google Scholar profile](https://scholar.google.com/citations?user=m5Hob3oAAAAJ&hl=en).

### Manuscript Under Review

- A. Islam, Md. R. Bin Mizan, M. Olshanskii, and A. Mang (2026).  
  *Tensorial Reduced-Order Models for Parametric Coupled Reaction-Diffusion Systems: Application to Brain Tumor Growth Modeling.*  
  arXiv:2603.14101. Under review. [arXiv](https://arxiv.org/abs/2603.14101)

### Manuscripts in Preparation

- A. Islam, P. Amiri, M. Olshanskii, and A. Mang.  
  *Discretize-then-optimize Parameter Estimation for Brain Tumor Growth Models using Tensorial ROMs.*  
  Manuscript in preparation.
- P. Amiri, A. Islam, and A. Mang.  
  *Correcting Reduced-Order Model Error in Tumor Growth Inversion via Hyper-Differential Sensitivity Analysis.*  
  Manuscript in preparation.

[Full publication list (PDF)](publications_list.pdf).

---

# Presentations

## Conference Presentations

- **2026:** Contributed talk, *Fast Tensorial Surrogate Models for Parametric Brain Tumor Growth Dynamics in Many-Query Regimes*, SIAM Annual Meeting, Cleveland, Ohio.
- **2025:** Poster presentation, CBMS Conference: Research at the Interface of Applied Mathematics and Machine Learning, University of Houston.
- **2025:** Poster presentation, SIAM Texas–Louisiana Sectional Meeting, University of Texas at Austin.
- **2025:** Poster presentation, ChAMELEON Summer School, University of Houston.

## Workshops and Professional Development

- **2026:** Bayesian Inverse Problems and Uncertainty Quantification Workshop, ICERM, Brown University.
- **2025:** CBMS Conference: Research at the Interface of Applied Mathematics and Machine Learning, University of Houston.
- **2025:** ChAMELEON Summer School, University of Houston.
- **2025:** Scientific Machine Learning Summer School, Texas A&M Institute of Data Science.
- **2025:** Firedrake 25 Workshop, Baylor University.
- **2022:** SIAM Texas–Louisiana Section Meeting, University of Houston.

---

# Service & Awards

## Awards and Honors

- **2025:** Best Poster Award, SIAM Texas–Louisiana Sectional Meeting, University of Texas at Austin.
- **August 2022–present:** Graduate Tuition Fellowship, University of Houston.
- **August 2022–present:** Teaching Assistantship, University of Houston.

## Professional Service and Volunteering

- **2026:** Volunteer, SIAM Annual Meeting, Cleveland, Ohio.
- **2025:** Volunteer, CBMS Conference: Research at the Interface of Applied Mathematics and Machine Learning, University of Houston.
- **2025:** Volunteer, ChAMELEON Summer School, University of Houston.
- **2022:** Volunteer, SIAM Texas–Louisiana Sectional Meeting, University of Houston.

## Professional Memberships

- American Mathematical Society (AMS), January 2023–present.
- Society for Industrial and Applied Mathematics (SIAM), August 2023–present.
- Bangladesh Mathematics Society (BMS), August 2017–present.
