## Order of Operations:
:PROPERTIES:
:heading: true
:END:
1. Extract events from fcs files
2. Process dimensions to info in fcs file
3. Apply compensation matrix if exists
## Questions/Topics:
### Debris Filtering
- does this need to happen before auto gating/custering?
- Appropriate auto gating / clustering strategies
- error checking
### Population Gating / Clustering
- Bead ID
- 1D vs 2D
- copying gates across files
- error checking
### CBA Plugin
- undefined classes in `FlowJoPeakFinderClustering`:
```java
        // Create a discrete function from the histogram array.
        DiscreteFunction DF = new DiscreteFunction(histogramData);

        // Create a PeakFinder object using the discrete function.
        PeakFinder PF = new PeakFinder(DF);
```
- 2dDensityGate --- [FlowGrid](https://github.com/VCCRI/FlowGrid)
###
---
title: Gating Notes
---

## Order of Operations:
:PROPERTIES:
:heading: true
:END:
1. Extract events from fcs files
2. Process dimensions to info in fcs file
3. Apply compensation matrix if exists
###
:PROPERTIES:
:heading: true
:END:
