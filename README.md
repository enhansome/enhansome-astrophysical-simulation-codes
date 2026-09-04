# Awesome Astrophysical Simulation Codes with stars

A curated list of awesome astrophysical simulation software

## Contents

* [Code List](#code-list)
* [Numerical Method](#numerical-method)
* [Physics](#physics)
* [High-Performance Features](#high-performance-features)
* [Additional Lists](#additional-lists)
* [Contribute](#contribute)

## Code List

| Code                                                                                                             | Description                                                                                                                | Lang.                                       | Repo                                                                                                                                  | Paper                                                                                                                                                                |
| ---------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Arepo](https://arepo-code.org/)                                                                                 | Massively parallel moving Voronoi mesh cosmological simulation code.                                                       | ![](https://skillicons.dev/icons?i=c)       | [![](https://skillicons.dev/icons?i=gitlab)](https://gitlab.mpcdf.mpg.de/vrs/arepo)                                                   | [<img src="https://ui.adsabs.harvard.edu/styles/img/transparent_logo.svg" width="45" height="40">](https://ui.adsabs.harvard.edu/abs/2010MNRAS.401..791S/abstract)   |
| [Athena++](https://www.athena-astro.app/)                                                                        | Radiation GRMHD code and adaptive mesh refinement (AMR) framework.                                                         | ![](https://skillicons.dev/icons?i=cpp)     | [![](https://skillicons.dev/icons?i=github)](https://github.com/PrincetonUniversity/athena) ⭐ 363 \| 🐛 30 \| 🌐 C++ \| 📅 2026-08-13 | [<img src="https://ui.adsabs.harvard.edu/styles/img/transparent_logo.svg" width="45" height="40">](https://ui.adsabs.harvard.edu/abs/2020ApJS..249....4S/abstract)   |
| [Castro](http://amrex-astro.github.io/Castro/)                                                                   | Adaptive mesh, rad/mhd/hydro simulation code for massively parallel CPU and GPU architectures.                             | ![](https://skillicons.dev/icons?i=cpp)     | [![](https://skillicons.dev/icons?i=github)](https://github.com/AMReX-Astro/Castro) ⭐ 339 \| 🐛 150 \| 🌐 C++ \| 📅 2026-09-01        | [<img src="https://ui.adsabs.harvard.edu/styles/img/transparent_logo.svg" width="45" height="40">](https://ui.adsabs.harvard.edu/abs/2010ApJ...715.1221A/abstract)   |
| [ChaNGa](https://faculty.washington.edu/trq/hpcc/tools/changa.html)                                              | Charm N-body Gravity solver and SPH.                                                                                       | ![](https://skillicons.dev/icons?i=c)       | [![](https://skillicons.dev/icons?i=github)](https://github.com/N-BodyShop/changa) ⭐ 55 \| 🐛 64 \| 🌐 C++ \| 📅 2026-08-03           | [<img src="https://ui.adsabs.harvard.edu/styles/img/transparent_logo.svg" width="45" height="40">](https://ui.adsabs.harvard.edu/abs/2011ascl.soft05005N/abstract)   |
| [Cholla](https://github.com/cholla-hydro/cholla/wiki) ⭐ 74 \| 🐛 35 \| 🌐 C++ \| 📅 2026-09-01                   | GPU-based hydro code.                                                                                                      | ![](https://skillicons.dev/icons?i=cpp)     | [![](https://skillicons.dev/icons?i=github)](https://github.com/cholla-hydro/cholla) ⭐ 74 \| 🐛 35 \| 🌐 C++ \| 📅 2026-09-01         | [<img src="https://ui.adsabs.harvard.edu/styles/img/transparent_logo.svg" width="45" height="40">](https://ui.adsabs.harvard.edu/abs/2016ascl.soft07006S/abstract)   |
| [Dedalus](https://dedalus-project.org/)                                                                          | Flexible framework for solving PDEs with modern spectral methods.                                                          | ![](https://skillicons.dev/icons?i=python)  | [![](https://skillicons.dev/icons?i=github)](https://github.com/DedalusProject/dedalus) ⭐ 704 \| 🐛 65 \| 🌐 Python \| 📅 2026-07-21  | [<img src="https://ui.adsabs.harvard.edu/styles/img/transparent_logo.svg" width="45" height="40">](https://ui.adsabs.harvard.edu/abs/2020PhRvR...2b3068B/abstract)   |
| [Einstein Toolkit](https://einsteintoolkit.org/)                                                                 | Community computational infrastructure for relativistic astrophysics.                                                      | ![](https://skillicons.dev/icons?i=cpp)     | [![](https://skillicons.dev/icons?i=github)](https://github.com/EinsteinToolkit)                                                      | [<img src="https://ui.adsabs.harvard.edu/styles/img/transparent_logo.svg" width="45" height="40">](https://ui.adsabs.harvard.edu/abs/2012CQGra..29k5001L/abstract)   |
| [Enzo](https://enzo-project.org/)                                                                                | Adaptive Mesh Refinement Code for Astrophysics.                                                                            | ![](https://skillicons.dev/icons?i=c)       | [![](https://skillicons.dev/icons?i=github)](https://github.com/enzo-project/enzo-dev) ⭐ 100 \| 🐛 79 \| 🌐 C \| 📅 2025-08-27        | [<img src="https://ui.adsabs.harvard.edu/styles/img/transparent_logo.svg" width="45" height="40">](https://ui.adsabs.harvard.edu/abs/2014ApJS..211...19B/abstract)   |
| [FLASH](https://flash.rochester.edu/site/flashcode/)                                                             | Adaptive Mesh Hydrodynamics Code for Modeling Astrophysical Thermonuclear Flashes.                                         | ![](https://skillicons.dev/icons?i=fortran) |                                                                                                                                       | [<img src="https://ui.adsabs.harvard.edu/styles/img/transparent_logo.svg" width="45" height="40">](https://ui.adsabs.harvard.edu/abs/2000ApJS..131..273F/abstract)   |
| [Gadget](https://wwwmpa.mpa-garching.mpg.de/gadget4/)                                                            | Parallel cosmological N-body and SPH code.                                                                                 | ![](https://skillicons.dev/icons?i=c)       | [![](https://skillicons.dev/icons?i=gitlab)](https://gitlab.mpcdf.mpg.de/vrs/gadget4)                                                 | [<img src="https://ui.adsabs.harvard.edu/styles/img/transparent_logo.svg" width="45" height="40">](https://ui.adsabs.harvard.edu/abs/2022ascl.soft04014S/abstract)   |
| [GAMER](https://github.com/gamer-project/gamer/wiki) ⭐ 104 \| 🐛 139 \| 🌐 C++ \| 📅 2026-08-14                  | GPU-accelerated Adaptive Mesh Refinement code for astrophysics.                                                            | ![](https://skillicons.dev/icons?i=cpp)     | [![](https://skillicons.dev/icons?i=github)](https://github.com/gamer-project/gamer) ⭐ 104 \| 🐛 139 \| 🌐 C++ \| 📅 2026-08-14       | [<img src="https://ui.adsabs.harvard.edu/styles/img/transparent_logo.svg" width="45" height="40">](https://ui.adsabs.harvard.edu/abs/2010ApJS..186..457S/abstract)   |
| [Gizmo](http://www.tapir.caltech.edu/~phopkins/Site/GIZMO.html)                                                  | Flexible, massively-parallel, multi-physics simulation code.                                                               | ![](https://skillicons.dev/icons?i=c)       | [![](https://skillicons.dev/icons?i=gitlab)](https://bitbucket.org/phopkins/gizmo-public/src/master/)                                 | [<img src="https://ui.adsabs.harvard.edu/styles/img/transparent_logo.svg" width="45" height="40">](https://ui.adsabs.harvard.edu/abs/2015MNRAS.450...53H/abstract)   |
| [MAESTROeX](https://amrex-astro.github.io/MAESTROeX/)                                                            | Massively parallel low Mach number stellar hydrodynamics code.                                                             | ![](https://skillicons.dev/icons?i=cpp)     | [![](https://skillicons.dev/icons?i=github)](https://github.com/AMReX-Astro/MAESTROeX) ⭐ 46 \| 🐛 30 \| 🌐 C++ \| 📅 2026-07-20       | [<img src="https://ui.adsabs.harvard.edu/styles/img/transparent_logo.svg" width="45" height="40">](https://ui.adsabs.harvard.edu/abs/2019ApJ...887..212F/abstract)   |
| [Nyx](https://amrex-astro.github.io/Nyx/)                                                                        | Adaptive mesh, cosmological hydrodynamics simulation code.                                                                 | ![](https://skillicons.dev/icons?i=cpp)     | [![](https://skillicons.dev/icons?i=github)](https://github.com/AMReX-Astro/Nyx) ⭐ 105 \| 🐛 8 \| 🌐 C++ \| 📅 2026-09-01             | [<img src="https://ui.adsabs.harvard.edu/styles/img/transparent_logo.svg" width="45" height="40">](https://ui.adsabs.harvard.edu/abs/2013ApJ...765...39A/abstract)   |
| [Pencil](http://pencil-code.nordita.org/)                                                                        | High-order finite-difference code for compressible hydrodynamic flows with magnetic fields and particles.                  | ![](https://skillicons.dev/icons?i=fortran) | [![](https://skillicons.dev/icons?i=github)](https://github.com/pencil-code/pencil-code) ⭐ 242 \| 🐛 0 \| 🌐 Fortran \| 📅 2026-09-04 | [<img src="https://ui.adsabs.harvard.edu/styles/img/transparent_logo.svg" width="45" height="40">](https://ui.adsabs.harvard.edu/abs/2010ascl.soft10060B/abstract)   |
| [PHANTOM](https://phantomsph.github.io/)                                                                         | Smoothed particle hydrodynamics and magnetohydrodynamics code for astrophysics.                                            | ![](https://skillicons.dev/icons?i=fortran) | [![](https://skillicons.dev/icons?i=github)](https://github.com/danieljprice/phantom) ⭐ 162 \| 🐛 77 \| 🌐 Fortran \| 📅 2026-09-03   | [<img src="https://ui.adsabs.harvard.edu/styles/img/transparent_logo.svg" width="45" height="40">](https://ui.adsabs.harvard.edu/abs/2018PASA...35...31P/abstract)   |
| [PLUTO](http://plutocode.ph.unito.it/)                                                                           | Code targeting high Mach number flows in astrophysical fluid dynamics.                                                     | ![](https://skillicons.dev/icons?i=c)       | [![](https://skillicons.dev/icons?i=github)](https://github.com/JohannesBuchner/PLUTO) ⚠️ Archived                                    | [<img src="https://ui.adsabs.harvard.edu/styles/img/transparent_logo.svg" width="45" height="40">](http://adsabs.harvard.edu/abs/2007ApJS..170..228M)                |
| [QUOKKA](https://quokka-astro.github.io/quokka/)                                                                 | First two-moment AMR radiation hydrodynamics on GPUs for astrophysics.                                                     | ![](https://skillicons.dev/icons?i=cpp)     | [![](https://skillicons.dev/icons?i=github)](https://github.com/quokka-astro/quokka) ⭐ 86 \| 🐛 251 \| 🌐 C++ \| 📅 2026-09-04        | [<img src="https://ui.adsabs.harvard.edu/styles/img/transparent_logo.svg" width="45" height="40">](https://ui.adsabs.harvard.edu/abs/2021ascl.soft10009W/abstract)   |
| [RAMSES](https://bytebucket.org/rteyssie/ramses/wiki/ramses_ug.pdf?rev=b6b7fef09b8bfe0d1e27c7d0c9edd584ec12768e) | Code to model astrophysical systems, featuring self-gravitating, magnetized, compressible, radiative fluid flows.          | ![](https://skillicons.dev/icons?i=fortran) | [![](https://skillicons.dev/icons?i=github)](https://github.com/miried/ramses) ⭐ 7 \| 🐛 0 \| 🌐 Fortran \| 📅 2024-09-23             | [<img src="https://ui.adsabs.harvard.edu/styles/img/transparent_logo.svg" width="45" height="40">](https://ui.adsabs.harvard.edu/abs/2002A%26A...385..337T/abstract) |
| [REBOUND](https://rebound.readthedocs.io/en/latest/)                                                             | Open-source multi-purpose N-body code.                                                                                     | ![](https://skillicons.dev/icons?i=c)       | [![](https://skillicons.dev/icons?i=github)](https://github.com/hannorein/rebound) ⭐ 1,122 \| 🐛 29 \| 🌐 C \| 📅 2026-08-26          | [<img src="https://ui.adsabs.harvard.edu/styles/img/transparent_logo.svg" width="45" height="40">](https://ui.adsabs.harvard.edu/abs/2012A%26A...537A.128R/abstract) |
| [SWIFT](https://swift.strw.leidenuniv.nl/)                                                                       | Modern highly-parallel gravity and smoothed particle hydrodynamics solver for astrophysical and cosmological applications. | ![](https://skillicons.dev/icons?i=c)       | [![](https://skillicons.dev/icons?i=github)](https://github.com/SWIFTSIM/SWIFT) ⭐ 158 \| 🐛 18 \| 🌐 C \| 📅 2026-09-04               | [<img src="https://ui.adsabs.harvard.edu/styles/img/transparent_logo.svg" width="45" height="40">](https://ui.adsabs.harvard.edu/abs/2023arXiv230513380S/abstract)   |
| [TARDIS](https://tardis-sn.github.io/)                                                                           | Fast 1D spectral code for supernovae with a vibrant community focused on training.                                         | ![](https://skillicons.dev/icons?i=python)  | [![](https://skillicons.dev/icons?i=github)](https://github.com/tardis-sn/tardis) ⭐ 241 \| 🐛 233 \| 🌐 Python \| 📅 2026-09-03       | [<img src="https://ui.adsabs.harvard.edu/styles/img/transparent_logo.svg" width="45" height="40">](https://ui.adsabs.harvard.edu/abs/2014MNRAS.440..387K/abstract)   |

## Numerical Method

| Code             | Finite Difference | Finite Volume | Finite Element | Spectral |   SPH   |  N-body | Eulerian |   ALE   | Lagrangian |       AMR       |
| ---------------- | :---------------: | :-----------: | :------------: | :------: | :-----: | :-----: | :------: | :-----: | :--------: | :-------------: |
| Arepo            |                   |    🟩️️️️️    |                |          |         | 🟩️️️️️ |          | 🟩️️️️️ |            |                 |
| Athena++         |                   |    🟩️️️️️    |                |          |         |         |  🟩️️️️️ |         |            |     🟩️️️️️     |
| Castro           |                   |    🟩️️️️️    |                |          |         |         |  🟩️️️️️ |         |            |     🟩️️️️️     |
| ChaNGa           |                   |               |                |          | 🟩️️️️️ | 🟩️️️️️ |          |         |   🟩️️️️️  |                 |
| Cholla           |                   |    🟩️️️️️    |                |          |         |         |  🟩️️️️️ |         |            |                 |
| Dedalus          |                   |               |                |  🟩️️️️️ |         |         |  🟩️️️️️ |         |            |                 |
| Einstein Toolkit |        🟩️        |      🟩️      |                |  🟩️️️️️ |         |         |  🟩️️️️️ |         |            |                 |
| Enzo             |                   |    🟩️️️️️    |                |          |         |         |  🟩️️️️️ |         |            |     🟩️️️️️     |
| FLASH            |                   |    🟩️️️️️    |                |          |         |         |  🟩️️️️️ |         |            |     🟩️️️️️     |
| Gadget           |                   |               |                |          | 🟩️️️️️ | 🟩️️️️️ |          |         |   🟩️️️️️  |                 |
| GAMER            |                   |    🟩️️️️️    |                |          |         |         |  🟩️️️️️ |         |            |     🟩️️️️️     |
| Gizmo            |                   |    🟩️️️️️    |                |          |         | 🟩️️️️️ |          |         |   🟩️️️️️  |                 |
| MAESTROeX        |                   |    🟩️️️️️    |                |          |         |         |  🟩️️️️️ |         |            |     🟩️️️️️     |
| Nyx              |                   |    🟩️️️️️    |                |          |         |         |  🟩️️️️️ |         |            |     🟩️️️️️     |
| Pencil           |      🟩️️️️️      |               |                |          |         |         |  🟩️️️️️ |         |            |                 |
| PLUTO            |      🟩️️️️️      |      🟩️      |                |          |         |         |  🟩️️️️️ |         |            |       🟩️       |
| PHANTOM          |                   |               |                |          | 🟩️️️️️ |   🟩️️  |          |         |   🟩️️️️️  |                 |
| QUOKKA           |                   |    🟩️️️️️    |                |          |         |         |  🟩️️️️️ |         |            | ️️️️️️️️🟩️️️️️ |
| RAMSES           |                   |    🟩️️️️️    |                |          |         | 🟩️️️️️ |  🟩️️️️️ |         |            |     🟩️️️️️     |
| REBOUND          |                   |               |                |          |         | 🟩️️️️️ |          |         |            |                 |
| SWIFT            |                   |               |                |          | 🟩️️️️️ | 🟩️️️️️ |          |         |   🟩️️️️️  |                 |
| TARDIS           |                   |               |                |  🟩️️️️️ |         |         |          |         |            |                 |

## Physics

| Code             | Hydrodynamics |   MHD   | Radiation | Self-Gravity | General-Relativity |
| ---------------- | :-----------: | :-----: | :-------: | :----------: | :----------------: |
| Arepo            |    🟩️️️️️    | 🟩️️️️️ |  🟩️️️️️  |    🟩️️️️️   |                    |
| Athena++         |    🟩️️️️️    | 🟩️️️️️ |  🟩️️️️️  |    🟩️️️️️   |       🟩️️️️️      |
| Castro           |    🟩️️️️️    | 🟩️️️️️ |  🟩️️️️️  |    🟩️️️️️   |                    |
| ChaNGa           |      🟩️      |         |           |      🟩️     |                    |
| Cholla           |      🟩️      |         |    🟩️    |      🟩️     |                    |
| Dedalus          |      🟩️      |   🟩️   |           |      🟩️     |                    |
| Einstein Toolkit |      🟩️      |   🟩️   |           |      🟩️     |         🟩️        |
| Enzo             |      🟩️      |   🟩️   |    🟩️    |      🟩️     |                    |
| FLASH            |      🟩️      |   🟩️   |    🟩️    |      🟩️     |                    |
| Gadget           |      🟩️      |         |           |      🟩️     |                    |
| GAMER            |    🟩️️️️️    | 🟩️️️️️ |  🟩️️️️️  |    🟩️️️️️   |                    |
| Gizmo            |      🟩️      |   🟩️   |    🟩️    |      🟩️     |                    |
| MAESTROeX        |      🟩️      |   🟩️   |    🟩️    |      🟩️     |                    |
| Nyx              |      🟩️      |   🟩️   |    🟩️    |      🟩️     |                    |
| Pencil           |      🟩️      |   🟩️   |           |      🟩️     |                    |
| PLUTO            |      🟩️      |   🟩️   |           |              |                    |
| PHANTOM          |      🟩️      |         |           |      🟩️     |                    |
| QUOKKA           |    🟩️️️️️    |         |  🟩️️️️️  |    🟩️️️️️   |                    |
| RAMSES           |      🟩️      |   🟩️   |    🟩️    |      🟩️     |                    |
| REBOUND          |               |         |           |      🟩️     |                    |
| SWIFT            |      🟩️      |         |           |      🟩️     |                    |
| TARDIS           |               |         |    🟩️    |              |                    |

## High-Performance Features

| Code             |   MPI   |   GPU   |
| ---------------- | :-----: | :-----: |
| Arepo            | 🟩️️️️️ |         |
| Athena++         | 🟩️️️️️ |         |
| Castro           | 🟩️️️️️ | 🟩️️️️️ |
| ChaNGa           | 🟩️️️️️ |         |
| Cholla           | 🟩️️️️️ | 🟩️️️️️ |
| Dedalus          |   🟩️   |         |
| Einstein Toolkit |   🟩️   |         |
| Enzo             |   🟩️   |         |
| FLASH            |   🟩️   |         |
| Gadget           |   🟩️   |         |
| GAMER            | 🟩️️️️️ | 🟩️️️️️ |
| Gizmo            |   🟩️   |         |
| MAESTROeX        |   🟩️   |   🟩️   |
| Nyx              |   🟩️   |   🟩️   |
| Pencil           |   🟩️   |         |
| PLUTO            | 🟩️️️️️ |         |
| PHANTOM          |   🟩️   |         |
| QUOKKA           |   🟩️   |   🟩️   |
| RAMSES           |   🟩️   |         |
| REBOUND          |   🟩️   |         |
| SWIFT            |   🟩️   |         |
| TARDIS           |         |   🟩️   |

## Additional Lists

* [HEP-ASTRO-COSMO](https://github.com/nikosarcevic/HEP-ASTRO-COSMO/blob/main/README.md#mhd) ⭐ 157 | 🐛 16 | 📅 2026-03-16

## Contribute

Contributions to the list are welcome! Contributing guidelines can be found in [CONTRIBUTING.md](CONTRIBUTING.md)

<!---
[![My Skills](https://skillicons.dev/icons?i=python)](https://skillicons.dev)
[![made-with-cpp](https://img.shields.io/badge/Made%20with-C++-1f425f.svg)](http://www.cplusplus.com/)
[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)
[![DOI](https://zenodo.org/badge/DOI/10.3847/1538-4365/ab929b.svg)](https://iopscience.iop.org/article/10.3847/1538-4365/ab929b)
-->

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-04._
