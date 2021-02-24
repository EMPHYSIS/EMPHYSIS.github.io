---
title: tools
permalink: /tools/
layout: default
toc: true
---

**Prototype** extensions of the following 13 tools have been developed in the EMPHYSIS project supporting
the [eFMI specification 1.0.0-alpha.4](https://emphysis.github.io/pages/downloads/efmi_specification_1.0.0-alpha.4.html):

![Tool support]({{ "/assets/images/tools.png" | relative_url }})

Explanations:

- _Lang to Beh. Model_: Generate Behavioral Model (= reference results) from modeling language
  (during the project, Behavioral Models have been semi-automatically generated via scripts
   from DLR-SR).

- _Lang to AlgCode_: Generate Algorithm Code from modeling language.

- _Alg to ProdCode_: Generate Production Code from Algorithm Code.

- _Prod to BinCode_: Generate Binary Code from Production Code.

- _test ProdCode_:\\
  The Production Code is compiled, executed with inputs defined in the
  Behavioral Model and the result compared with the outputs defined in the Behavioral Model.

- _verify ProdCode_:\\
  Analysis of Production Code for run-time errors and (MISRA) rule violations.
  
- In the right part of the figure some incomplete developments are listed that
  are planned to be continued after the EMPHYSIS project:
  The _Equation Code_ describes a set of Differential-Algebraic Equations in a
  neutral form. It shall be a strict subset of the [flat Modelica definition](https://github.com/modelica/ModelicaSpecification/blob/MCP/0031/RationaleMCP/0031/ReadMe.md)
  under development from EMPHYSIS and Modelica Association partners.

- _Lang to EquCode_: Generate Equation Code from modeling language.

- _Equ to AlgCode_: Generate Algorithm Code from Equation Code.