%![PhyOrg](PhysOrg.png)
# Extreme ester Hydrolysis
As we explore physical organic chemistry we can investigate seemingly simple reactions and observe surprising complexity. This webbook is a collection of documents and data analysis exploring the acid hydrolysis of esters. There are several possible mechanisms that can consume the starting material depending on the structure of the ester and the strength of the acidic conditions. We will be considering acid mixtures far beyond where the pH scale has meaning. Lets get extreme, together. 

## Contents

I first began this line of thought after presenting some work of Keith Yates (1928-2006) and Robert McClelland performed at the University of Toronto and reported in 1967. Both had long careers at U of T and McClelland continues there as a Professor Emeritus.

"Mechanisms of ester hydrolysis in aqueous sulfuric acids." K. Yates, R.A. McClelland, *J. Am. Chem. Soc.*, **1967**, *89*, 2686-2692. https://doi.org/10.1021/ja00987a033

This paper presents a complicated relationship between reactivity and acidity. It also provides evidence supporting an idea that ester hydrolysis is second-order in water. I worked through the data in the paper and presented an analysis of the results for methyl acetate in the following documents.

### Discussion of Yates \& McClellan, 1967

[EsterAcidHydrolysisExploration.pdf](pdf/EsterAcidHydrolysisExploration.pdf) - This document presents my analysis of the results in the paper. Python notebooks that generated data transformations and plots are listed below.

- [Figure 5](notebooks/01_Yates-Fig5-HRH0.ipynb) - Plot of $H_r$ vs $H_0$
- [Figure 5](notebooks/01_Yates-Fig5-HRH0+interpolatorsH0HR-Patches.ipynb) - Same as above but with plots of interpolations of $H_r$ vs $H_0$ data sets.
- [Figure 6](notebooks/01_Yates-Fig6-MeOAc.ipynb) - Plot of $k_{obs}$ vs $[H_2SO_4]$
- [Figure 7](notebooks/01_Yates-Fig7-MeOAc.ipynb) - Plot of $k_{obs}$ vs $H_0$
- [Figures 8 \& 9](notebooks/01_Yates-Fig8-rate_vs_aH2O.ipynb) - Plot of $k_{obs} + H_0$ vs $a_{H_2O}$ and plot of residuals

