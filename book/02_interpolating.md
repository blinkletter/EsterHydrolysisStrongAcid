%![PhyOrg](PhysOrg.png)
# Interpolating Literature Data Sets

I wanted to analyze the data using data sets for $H_0$ and $a_{H_2O} from sources other that the values reported in Yates \& McClellan, 1967. If the values in a data set did not align with those used by the authors we will need to use interpolation to estimate the values in the spaces between data points.  

## Table of Contents

[EsterAcidHydrolysisExploration.pdf](pdf/Interpolators_1.pdf) - This document presents efforts to understand and use interpolation in data sets. Calculations and figures presented in this exploration are documented in the *Python* notebook below.

- [Figures](notebooks/02_Yates-interpolators.ipynb) - Plots of the following...
    - Figure 1: Plot of data for $a_{H_2O}$ vs \%wt $\%{H_2SO_4}$ with interpolation line; plot of \%differential between data and interpolation.
    - Figure 2: Plot of data for $H_0$ vs \%wt ${H_2SO_4}$ with interpolation line; plot of \%differential between data and interpolation.
    - Figure 3: Plot of data for density vs \%wt ${H_2SO_4}$ with interpolation line; plot of \%differential between data and interpolation.
- [Early Work](notebooks/02_interpolators_check.ipynb) - Some scratch work will I was poking around with the tools. Archived here so that I can reuse the code if needed.

The following notebooks are purpose-built to provide interpolated values from valrious data sets. 

- [$a_{H_2O}$ vs $\%{H_2SO_4}$](notebooks/02_01A-ActivityOfWaterinH2SO4byWt.ipynb) - An interpolator that will estimate the value of $a_{H_2O}$ when given $%H_2SO_4$.
- [$a_{H_2O}$ vs mole fraction $H_2SO_4$](notebooks/02_01B-ActivityOfWaterinH2SO4byX.ipynb) - An interpolator that will estimate the value of $a_{H_2O}$ when given the mole fraction of $H_2SO_4$.
- [Plots of $H_0$ vs $\%{H_2SO_4}$](notebooks/02_02_H2SO4_PercentWt_to_H0.ipynb) - various data tables for $H_0$ vs $\%H_2SO_4$ are compared.
- [Density vs $\%H_2SO_4$](notebooks/02_03_H2SO4_Percent_Density_Molarity.ipynb) - Interpolations of a date set for density vs $\%H_2SO_4$ and a plot of molarity of $H_2SO_4$ vs $\%$
- [Molarity from $\%H_2SO_4$](notebooks/02_03_H2SO4_PercentWt_to_MolarConc.ipynb) - More examples of calulating molarity from $\%H_2SO_4$. Includes use of "patches" to draw rectangles on plots.
- [$H_R$ values](notebooks/02_04_Cook_1975_HR_Values_Smooth.ipynb) - interpolations of density and molarity from $\%H_2SO_4$. Interpolation of $H_R$ values.
- [$H_R$ and $H_0$](notebooks/02_04_H0_HR_Comparison.ipynb) - Plots comparing acidity functions $H_R$ and $H_0$
