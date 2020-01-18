# Effect-size

# 1. ANOVA: interaction
library(sjstats)
library(car)
omega_sq(Interaction_AA)
##Field (2013) suggests the following interpretation heuristics:
##Omega Squared = 0 - 0.01: Very small
##Omega Squared = 0.01 - 0.06: Small
##Omega Squared = 0.06 - 0.14: Medium
##Omega Squared > 0.14: Large
