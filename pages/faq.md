---
title: FAQ
permalink: /faq/
layout: default
toc: true
---

# General questions about EMPHYSIS and eFMI

## When will eFMI 1.0.0 be released?

 EMPHYSIS partners have sent an application to the Modelica Association to form a _Modelica Project eFMI_.
 Once founded, the new eFMI group will try to quickly release the eFMI specification as
 Modelica Association standard. A concrete release date is not yet known.

## What will be the license and usage conditions for the planned eFMI standard?

Access and use of the eFMI standard will be free of charge. 

**To be clear: While the eFMI standard will be open and free, commercial tool support might not be.**


## How is eFMI related to FMI?

- eFMI will have different packaging format. The main packaging format will be an FMU for Co-Simulation
  where the eFMI definition is stored under directory _extras/org.efmi-standard_.
  This means that every tool supporting FMI for Co-Simulation should be able to simulate
  the eFMU.
 
- Technically, eFMI is using a few definitions from FMI 3.0, but otherwise can be seen as a complementary technology.


## How is eFMI related to Modelica?

- Technically eFMI is not related to Modelica, and can be seen as a complementary technology.
- The intention of the eFMI project is to be neutral with respect to tools, technologies (e.g. solvers, OS, files, systems…) and languages (including Modelica).
- The eFMI standard shall be further developed as a Modelica Association Project within the Modelica Association, an organization focused on the “coordinated standardization and development of software technology and methods in the area of cyber physical- systems and systems engineering”, see the Modelica Association Bylaws and the History page
