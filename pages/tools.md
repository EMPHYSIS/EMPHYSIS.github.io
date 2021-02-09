---
title: tools
permalink: /tools/
layout: default
toc: true
---

The following 10 tools have been extended in the EMPHYSIS project to support
the (eFMI specification 1.0.0-alpha.3)[https://emphysis.github.io/pages/downloads/efmi_specification_1.0.0-alpha.3.html] 
in form of **prototype** extensions:

| Tool                 | Vendor                              | Supported eFMI Features                          |
|:---------------------|:------------------------------------|:-------------------------------------------------|
| **AUTOSAR Builder**  | Dassault Systèmes                   | Production and Binary Code -> Adaptive AUTOSAR   |
| **Astrée**           | AbsInt GmbH                         | Verification of Production Code                  |
| **CSD**              | Siemens NV                          | Test and verification of Production Code         |
| **Dymola**           | Dassault Systèmes AB                | Modelica -> Algorithm Code and Behavioral Model  |
| **ESP**              | Dassault Systèmes                   | Production Code -> Binary Code                   |
| **SCODE CONGRA**     | ETAS GmbH                           | Algorithm Code -> Production Code + test of code |
| **Simcenter Amesim** | Siemens Digital Industries Software | Amesim model -> neural network approx. as Algorithm Code|
| **SimulationX**      | ESI ITI GmbH                        | Modelica -> Algorithm Code                       |
| **TargetLink**       | dSPACE GmbH                         | Algorithm Code -> Production Code + test of code |
| **TPT**              | PikeTec                             | Test of Production Code                          |
 
  
_Test of Production Code_ and _Test of code_ mean to compile the Production C-Code, execute it with
inputs defined in the Behaviorial Model and compare with the reference results stored in the Behavioral Model.