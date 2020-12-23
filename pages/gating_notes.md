## Order of Operations:
:PROPERTIES:
:heading: true
:END:
### 1. Extract events from fcs files
2. Process dimensions to info in fcs file
3. Apply compensation matrix if exists
## Questions/Topics:
:PROPERTIES:
:heading: true
:END:
- Debris Filterinig
- Population Gating / Clustering
- CBA Plugin
## Debris Filtering
:PROPERTIES:
:heading: true
:END:
- does this need to happen before auto gating/custering?
- Appropriate auto gating / clustering strategies
- error checking
## Population Gating / Clustering
:PROPERTIES:
:heading: true
:END:
- Bead ID
- 1D vs 2D
- copying gates across files
- error checking
## CBA Plugin
:PROPERTIES:
:heading: true
:END:
- undefined classes in `FlowJoPeakFinderClustering`:
```java
        // Create a discrete function from the histogram array.
        DiscreteFunction DF = new DiscreteFunction(histogramData);
        // Create a PeakFinder object using the discrete function.
        PeakFinder PF = new PeakFinder(DF);
        // Create a PeakList to store the peaks found from PeakFinder().
        PeakList peakList = PF.findPeaks(PeakFinder.PeakFind_IgnoreBottom15Percent);
```
- 2dDensityGate --- [FlowGrid](https://github.com/VCCRI/FlowGrid)
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
