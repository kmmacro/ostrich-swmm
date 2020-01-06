# OSTRICH-SWMM

A toolset for connecting the Optimization Software Toolkit for Computational Heuristics (OSTRICH) with the Stormwater Management Model (SWMM).

#### Process Flow Diagram



![](C:\PROJECTCODE\ostrich-swmm\static\OSTRICH-SWMM-process-diagram.png)

#### Optimization Features:

- Parallel processing
- Single- or multi-objective optimization using any algorithm available in OSTRICH. See the [OSTRICH Documentation](<http://www.eng.buffalo.edu/~lsmatott/Ostrich/OstrichMain.html>) for more details.

#### LID Optimization Modules

Modules for optimizing the size, type, and location of Low Impact Development (LID) projects in a SWMM model. This version of OSTRICH-SWMM includes modules for:

- Rain Barrels (RB) 
  - Simulates rooftop disconnection and routing to rain barrel within the impervious area of subcatchments
- Permeable Pavement (PP)
  - Simulates conversion of subcatchment impervious area to permeable pavement

## Running OSTRICH - SWMM

#### ostrich-swmm.sh

```
ostrich-swmm run -c ostrich-swmm-config.json
```

An example config file can be found here: ostrich-swmm/templates/ostrich-swmm-config.json