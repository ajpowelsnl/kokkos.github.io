---
authors: ["kokkos-team"]
title: "Applications"
date: "2023-01-01"
tags: ["Applications", "AppName"]
---

The following is a partial list of applications leveraging Kokkos for Performance Portability. The “Status” field indicates whether the application is using Kokkos in productions runs yet, or whether the project is in the process or porting over to Kokkos or developing its capabilities from scratch.

|          AppName          |                                          Area                                         |        Institution        |                    Website                   |           Status           | Uses KokkosKernels |             Contact Name             |                  Contact Email                 |
|:-------------------------:|:-------------------------------------------------------------------------------------:|:-------------------------:|:--------------------------------------------:|:--------------------------:|:------------------:|:------------------------------------:|:----------------------------------------------:|
| Albany                    | Climate                                                                               | Sandia                    | https://github.com/gahansen/Albany           | Porting                    | Y                  | Andy Salinger                        | –                                              |
| LGR                       | Shock Hydrodynamics                                                                   | Sandia                    | https://github.com/SNLComputation/lgrtk      | Production                 | Y                  | Dan Ibanez                           | daibane@sandia.gov                             |
| Aria                      | Thermal Fluid Multi Physics                                                           | Sandia                    |                                              | Porting                    | Y                  | Jonathan Clausen                     | jclause@sandia.gov                             |
| LAMMPS                    | Molecular Dynamics                                                                    | Sandia                    | https://github.com/lammps/lammps             | Production                 | N                  | Stan Moore                           | –                                              |
| Trilinos-Tpetra           | Distributed Sparse Linear Algebra Package                                             | Sandia                    | https://github.com/trilinos/trilinos         | Production                 | Y                  | Karen Devine                         | –                                              |
| Trilinos-Phalanx          | DAG-based Assembly                                                                    | Sandia                    |                                              | Production                 | Y                  | Roger Pawlowski                      | rppawlo@sandia.gov                             |
| Trilinos-Panzer           | Finite Element Tools                                                                  | Sandia                    |                                              | Production/Porting         | Y                  | Roger Pawlowski                      | rppawlo@sandia.gov                             |
| Trilinos – ShyLU Basker   | Sparse Direct Solver                                                                  | Sandia                    | https://github.com/trilinos/Trilinos         | Porting/Production         | N                  | Nathan Ellingwood, Siva Rajamanickam | ndellin@sandia.gov                             |
| Trilinos – ShyLU Tacho    | Tasking Cholesky Solver                                                               | Sandia                    | https://github.com/trilinos/Trilinos         | Porting/Production         | N                  | Kyungjoo Kim, Siva Rajamanickam      | kyukim@sandia.gov                              |
| Drekar                    | Turbulent CFD, MHD, Plasma Physics                                                    | Sandia                    |                                              | Production/Porting         | Y                  | Roger Pawlowski                      | rppawlo@sandia.gov                             |
| MTGL                      | Graph Library                                                                         | Sandia                    | N/A                                          | Porting/Production         | N                  | Jon Berry                            | jberry@sandia.gov                              |
| Parallel Research Kernels | Programming Models Research                                                           | Intel Corporation         | https://github.com/ParRes/Kernels            | Evaluation                 | N                  | Jeff Hammond                         | jeff_hammond@acm.org                           |
| Compadre Toolkit          | Compatible remap and PDE solution on particles using Generalized Moving Least Squares | Sandia                    | –                                            | Production                 | N                  | Paul Kuberry                         | pakuber@sandia.gov                             |
| HOMMEXX                   | Atmospheric Dynamics for Climate Simulations                                          | Sandia                    |                                              | Production                 | Y                  | Andy Salinger                        | agsalin@sandia.gov                             |
| MiniMD                    | Molecular Dynamics Proxy App                                                          | Sandia                    | https://github.com/mantevo/minimd            | Production                 | N                  | Christian Trott                      | crtrott@sandia.gov                             |
| ExaMiniMD                 | Molecular Dynamics Proxy App                                                          | Sandia                    | https://github.com/ecp-copa/examinimd        | Production                 | N                  | Christian Trott                      | crtrott@sandia.gov                             |
| MiniFE                    | Finite Element Proxy App                                                              | Sandia                    | https://github.com/mantevo/minife            | Production                 | N                  | Christian Trott                      | sdhammo@sandia.gov                             |
| AllRegime                 | CFD, All Mach number Hydrodynamics on regular grids                                   | CEA                       | –                                            | Porting                    | N                  | Thomas Padioleau                     | thomas.padioleau@cea.fr                        |
| ppkMHD                    | CFD, High order schemes for high Mach number MHD applications in astrophysics         | CEA                       | –                                            | Porting                    | N                  | Pierre Kestener                      | pierre.kestener@cea.fr                         |
| LBM_saclay                | Lattice Boltzmann methods for multiphase flow                                         | CEA                       | –                                            | Evaluation                 | N                  | Alain Cartalade / Pierre Kestener    | alain.cartalade@cea.fr; pierre.kestener@cea.fr |
| IOSS                      | Finite Element I/O library                                                            | Sandia                    | https://github.com/gsjaardema/seacas         | Porting                    | N                  | Greg Sjaardema                       | gdsjaar@sandia.gov                             |
| SPARC                     | CFD                                                                                   | Sandia                    | N/A                                          | Porting/Production         | Y                  | –                                    | –                                              |
| EMPIRE                    | PIC                                                                                   | Sandia                    | N/A                                          | Porting/Production         | Y                  | –                                    | –                                              |
| Gemma                     | Electromagnetic Radiation (EMR)                                                       | Sandia                    | N/A                                          | Development                | N                  | William Langston                     |                                                |
| SPARTA                    | DSMC                                                                                  | Sandia                    | https://github.com/sparta/sparta             | Porting                    | N                  | –                                    | –                                              |
| EnGPar                    | dynamic load balancing                                                                | RPI SCOREC                | http://scorec.github.io/EnGPar/              | Porting                    | Y                  | Cameron Smith                        | smithc11@rpi.edu                               |
| K-Athena                  | CFD, Astrophysical MHD                                                                | Michigan State University | tba                                          | Porting                    | N                  | Philipp Grete                        | grete@pa.msu.edu                               |
| Nalu-Wind                 | Ecp/Exawind application                                                               | NREL/Sandia               | https://github.com/exawind/nalu-wind         | Porting/Production         | N                  | Alan Williams                        | william@sandia.gov                             |
| STK                       | Sierra Toolkit                                                                        | Sandia                    | N/A                                          | Porting/Production         | N                  | Alan Williams                        | william@sandia.gov                             |
| GenTen                    | Tensor decompositions                                                                 | Sandia                    | https://gitlab.com/tensors/genten            | Porting/Production         | N                  | Eric Phipps                          | etphipp@sandia.gov                             |
| DataTransferKit           | solution transfer services for multiphysics applications                              | ORNL                      | https://github.com/ORNL-CEES/DataTransferKit | Production                 | N                  | Stuart Slattery                      | slatterysr@ornl.gov                            |
| E3SM                      | High-res, cloud-resolving atmosphere model (SCREAM)                                   | DoE                       | https://github.com/E3SM-Project/scream       | Development                | N                  | Jim Foucar                           | jgfouca@sandia.gov                             |
| COMPOSE                   | Earth Sciences                                                                        | SNL                       | https://github.com/E3SM-Project/COMPOSE      | Production and Development | N                  | Andrew M. Bradley                    | ambradl@sandia.gov                             |
| Sunata                    | Metal Additive Manufacturing                                                          | Atlas3D                   | https://atlas3d.xyz/                         | Production and Development | Y                  | Hao Peng                             | hao@atlas3d.xyz                                |
| BabelStream               | Benchmarking                                                                          | University of Bristol     | http://uob-hpc.github.io/BabelStream/        | Production                 | No                 | Tom Deakin                           | tom.deakin@bristol.ac.uk                       |