# Analytical view of correlated uncertainties
## Combined uncertainty in simple operations. Addition and subtraction.

When two input quantities of a model are correlated, this correlation must be taken into account when estimating the combined uncertainty.

This exercise aims to evaluate the effect of the correlation between two input quantities on their combined uncertainty. The measurand of interest is the distance of a string. To obtain the input quantities, or distances, we make use of two rulers. The fact that these two rulers were probably calibrated according to similar standards and the same correction factor was applied to account for systematic errors, and also that they have been scaled with comparable accuracy might make these measurements correlated.
We take N measurements with each ruler and obtain a mean value (L1_mean, L2_mean). The error in the measurement (U_ruler1, U_ruler2) is the standard deviation of the N measurements, and is associated with the shortest distance measurable by each ruler, with a coverage factor k.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/PacoCosta/AnalyticView_UncertaintyCorrelations.git/HEAD)
