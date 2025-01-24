# MAST-1D - Sand & Mud - Minnesota River
Morphodynamics and Sediment Tracers in 1-D (MAST 1-D) - Minnesota River Version

This repository is a work in progress. It contains source codes and published papers with the description of models of river morphodynamics with an off-channel sediment reservoir representing an alluvial floodplain. The mathematical formulation was first implemented by Lauer and Parker (2008a, b, c) and subsequently modified by Viparelli et al., (2013), Lauer et al., (2016), DeRego et al. (2020), Viparelli and Eke (2021). 

There are two main versions of MAST-1D, one for sand bed rivers (Lauer and Parker, 2008a,b; Viparelli et al., 2013, Viparelli and Eke, 2021) and the other for gravel bed rivers (Lauer et al., 2016, DeRego et al., 2020). 

Models are either VBA macros embedded in excel workbooks or python scripts. Programming in VBA was convenient when models were first developed and tested because it allowed the collaboration with resarchers who did not have programming expertise. 

This repository contains excel files with embedded VBA macros used for the Minnesota River application of the MAST-1D version for sand bed rivers. 
The repository with files related to the analytical solution to predict the equlibrium channel geometry is https://github.com/vipenrica/Channel-geometry
The repository of the gravel bed river version, which is written in python and is maintained by Wes Lauer, is https://github.com/MAST-1D/MAST-1D-2.0. 

Excel files with different sub-models to compute channel migration are uploaded in this repository. Equilibrium files contain the Viparelli and Eke (2021) analytical model with various sub-models to compute annual migration rate and point bar height. Transient files contain version of the full model differing for the approach to compute annual migration rate and point bar height. File extension 'sf' indicate that bank migrations are computed with the Eke et al. (2014) model so that channel width and point bar height are both allowed to change in space and time. File extension 'eng' indicates that channel banks are not allowed to migrate independently; centerline migration rate and point bar height are computed as in Ikeda et al. (1981). File extension 'fix' indicates the mean annual channel migration rate and point bar height are specified values that do not vary in space and time, as in Viparelli et al. (2013). 

REFERENCES

De Rego, K., Lauer, J.W., Eaton, B., & Hassan, M. (2020). A decadal-scale numerical model for wandering, cobble-bedded rivers subject to disturbance. Earth Surface Processes and Landforms, 45, 912–927.

Eke, E., Parker, G. & Y. Shimizu (2014). Numerical modeling of erosional and depositional bank processes in migrating river bends with self-formed width: Morphodynamics of bar push and bank pull, Journal of Geophysical Research: Earth Surface 119, 1455-1483.

Ikeda, S., Parker, G. & K. Sawai, (1981). Bend theory of river meanders. Part 1. Linear development, Journal of Fluid Mechanics 112, 363-377.

Lauer, J.W., & Parker, G. (2008a). Modeling framework for sediment deposition, storage, and evacuation in the floodplain of a meandering river: Theory. Water Resources Research, 44, W04425. 

Lauer, J.W., & Parker, G. (2008b). Modeling framework for sediment deposition, storage, and evacuation in the floodplain of a meandering river: Application to the Clark Fork River, Montana. Water Resources Research, 44, W08404. 

Lauer, J.W. & Parker, G. (2008c). Net local removal of floodplain sediment by river meander migration. Geomorphology, 96, 123-149. 

Lauer, J. W., and J. Willenbring (2010), Steady state reach‐scale theory for radioactive tracer concentration in a simplechannel/floodplain system, Jourbal of Geophysical Research, 115, F04018.

Lauer, J.W., Viparelli, E., & Piegay, H. (2016). Morphodynamics and sediment tracers in 1-D (MAST-1D): 1-D sediment transport that includes exchange with an off-channel sediment reservoir. Advances in Water Resources, 93, 135–149.

Viparelli, E., Lauer, J. W., Belmont, P. & Parker, G. (2013). A numerical model to develop long-term sediment budgets using isotopic sediment fingerprints, Computers & Geosciences 53, 114-122.

Viparelli, E., & Eke, E.C. (2021). Equilibrium of self-formed, single-thread, sand-bed rivers. Geophysical Research Letters, 48, e2021GL094591.







