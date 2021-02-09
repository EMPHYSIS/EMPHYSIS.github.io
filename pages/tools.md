---
title: tools
permalink: /tools/
layout: default
toc: true
---

**Prototype** extensions of the following 13 tools have been developed in the EMPHYSIS project to support
the [eFMI specification 1.0.0-alpha.3](https://emphysis.github.io/pages/downloads/efmi_specification_1.0.0-alpha.3.html):

![Tool support]({{ "/assets/images/tools.png" | relative_url }})

Explanations:

- _test ProdCode_:\\
  The Production C-Code is compiled, executed with inputs defined in the
  Behavioral Model and the result compared with the outputs defined in the Behavioral Model.

- -verify ProdCode_:\\
  Analysis of Production C-Code for run-time errors and (MISRA) rule violations.
  
- In the right part of the figure some incomplete developments are listed that
  are planned to be continued after the EMPHYSIS project:
  The _Equation Code_ describes a set of Differential-Algebraic Equations in a
  neutral form. It shall be a strict subset of the [flat Modelica definition](https://github.com/modelica/ModelicaSpecification/blob/MCP/0031/RationaleMCP/0031/ReadMe.md)
  under development from EMPHYSIS and Modelica Association partners.

