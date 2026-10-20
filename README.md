<div align="left">
  <a href="https://www.tum.de" target="_blank">
    <img src="./tum.png" alt="Technical University of Munich" height="80"/>
  </a>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://www.oth-regensburg.de" target="_blank">
    <img src="./oth.jpg" alt="OTH Regensburg" height="80"/>
  </a>
</div>

# Christoph Hollweck

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Christoph_Hollweck-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/christoph-hollweck-5962ab231/)
[![Email](https://img.shields.io/badge/Email-hollweck.christoph%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:hollweck.christoph@gmail.com)
[![IGAeasy](https://img.shields.io/badge/GitHub-IGAeasy-181717?style=flat&logo=github&logoColor=white)](https://github.com/christophhollweck/IGAeasy)

PhD candidate in **Computational Mechanics** at the **Technical University of Munich** and research associate at **OTH Regensburg**.

My research focuses on numerical methods for **isogeometric analysis (IGA)** and **nonlinear structural dynamics**, with particular emphasis on CAD-integrated analysis, trimmed geometries, local refinement, and explicit dynamics.

## Research Interests

- Isogeometric analysis
- Finite element methods
- Computational mechanics
- Explicit structural dynamics
- CAD and B-rep geometry processing
- Trimmed and multi-patch spline geometries
- LR-splines and THB-splines
- Local h-, p-, and k-refinement
- Shell formulations
- Critical time-step analysis and mass scaling
- Sheet-metal forming

## IGAeasy

I develop **[IGAeasy](https://github.com/christophhollweck/IGAeasy)**, an open-source Python framework for isogeometric structural analysis.

The framework connects my research in computational mechanics with scientific software development. Its modular structure covers geometry, spline discretization, numerical integration, assembly, solution, and interactive postprocessing.

The current public release focuses on **linear static membranes and shells**, with support for:

- **Locally refined LR- and THB-splines**
- **Fitted and trimmed geometries**
- **Membrane, Reissner-Mindlin shell, and Kirchhoff-Love shell formulations**
- **Verification through analytical and manufactured solutions, convergence studies, structural benchmarks, and automated regression tests**

The repository includes runnable examples, verification studies, and documentation of the supported formulations and known limitations.

**[Explore the repository, examples, and documentation →](https://github.com/christophhollweck/IGAeasy)**

The visualizations below were generated with **IGAeasy**.

<div align="left">
  <img src="./basis.png" alt="Spline basis functions generated with IGAeasy" height="300"/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="./Gengar.png" alt="Trimmed isogeometric geometry generated with IGAeasy" height="300"/>
</div>

## Selected Publications

### Explicit Dynamics and Trimmed Spline Spaces

**C. Hollweck, L. F. Leidinger, S. Hartmann, M. Wagner, R. Wüchner**  
[**An analysis of the critical time step size for explicit dynamics using trimmed B-splines, LR-splines, and THB-splines**](https://doi.org/10.1016/j.cma.2025.118656)  
*Computer Methods in Applied Mechanics and Engineering*, 450, 118656, 2026.

**C. Hollweck, L. F. Leidinger, S. Hartmann, M. Wagner, R. Wüchner**  
[**Boundary-Level-Constrained Refinement for Suppressing Trimming-Induced High-Frequency Outliers in Explicit Isogeometric Analysis**](https://arxiv.org/abs/2609.10161)  
arXiv:2609.10161, 2026. Under review at *Computer Methods in Applied Mechanics and Engineering*.

### Local Refinement and Shifted Boundary Method

**C. Hollweck, A. Gorgi, N. Antonelli, M. Wagner, R. Wüchner**  
[**Local h-, p-, and k-Refinement Strategies for the Isogeometric Shifted Boundary Method Using THB-Splines**](https://arxiv.org/abs/2512.17666)  
arXiv:2512.17666, 2025. Under review at *Computational Mechanics*.

## Current Research Topics

My current work includes:

- Numerical methods for trimmed isogeometric discretizations
- Explicit dynamics with B-splines, LR-splines, and THB-splines
- Critical time-step and spectral analysis
- Local mass scaling for trimming-induced high-frequency outliers
- Local refinement of trimmed shell geometries
- CAD-to-analysis workflows and BEXT-based data exchange
- Industrial applications of isogeometric analysis in LS-DYNA

## Academic Supervision

**Prof. Dr.-Ing. habil. Roland Wüchner**  
Chair of Structural Analysis, Technical University of Munich  
[Chair of Structural Analysis](https://www.cee.ed.tum.de/st/startseite/)

**Prof. Dr.-Ing. Marcus Wagner**  
Finite Element Methods Laboratory, OTH Regensburg  
[Finite Element Methods Laboratory](https://maschinenbau.oth-regensburg.de/labore/fem)
