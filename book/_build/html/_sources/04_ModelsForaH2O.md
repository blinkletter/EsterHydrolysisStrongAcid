%![PhyOrg](PhysOrg.png)
# Models for $a_{H_2O}$ and More

To analyze the data in the paper of Yates and McClellan I needed a way to match the  

## Table of Contents

[Models_aH2O_and_More.pdf](pdf/Models_aH2O_and_More.pdf) - This document explores the idea of creating polynomial curve fits for the data sets discussed in the [interpolation page](02_interpolating.md). In the end, I settled on a better form of interpolation. The following notebooks contain the code for the plots and data analysis.

- [Figures 2 to 14](notebooks/04_ParameterizedModels.ipynb) - Plots of the following...
    - Figure 1: Plots of differences between calculated values and table values for molarity and for $\%H_2SO_4$ when using molality as source data.
    - Figure 2: Plot of $\rho$ vs $w$ for data sets of Perry, Rhodes and Oca at 25 ◦C
    - Figure 3: Plot of $\rho$ vs $w$ for data sets of Perry, Kaye and Oca at 20 ◦C
    - Figure 4: Plots of 4<sup>th</sup>-degree polynomial models for density vs $\%H_2SO_4$ compared with the model of Hyvärinen
    - Figure 5: Plots of 6<sup>th</sup>-degree polynomial models for density vs $\%H_2SO_4$ compared with the model of Oca
    - Figure 6: Plots of density vs $\%H_2SO_4$ with a spline interpolation.
    - Figure 7: Plots $a_{H_2O}$ vs $w$ for the data sets of Giauque, Rard, and Staples.
    - Figure 8: Plots of 20<sup>th</sup>-degree polynomial models for $a_{H_2O}$ vs $\%H_2SO_4$.
    - Figure 9: Plots of piecewise polynomial models for $a_{H_2O}$ vs $\%H_2SO_4$.
    - Figure 10: Plots of 12<sup>th</sup>-degree  polynomial models for $\log{a_{H_2O}}$ vs $\%H_2SO_4$.
    - Figure 11: Plots comparing linear and spline interpolations for $a_{H_2O}$ vs $\%H_2SO_4$ with the piecewise polynomial model from Figure 9.
    - Figure 12: Plots $H_0$ vs $\%H_2SO_4$ for various data sets available in the literature.
    - Figure 13: Plots of polynomial models for $H_0$ vs $\%H_2SO_4$.
    - Figure 14: Plots of spline interpolation for $H_0$ vs $\%H_2SO_4$.

- [Figures 15, 16 \& 18 ](notebooks/04_cox.ipynb) - Plots of the following...
    - Figure 15: Plot of $a^M_{H_2O}$ (Molar) vs $\%H_2SO_4$ comparing the data sets of Giaques and Cox.
    - Figure 16: Plot of $\log{a^M_{H_2O}}$ vs $\%H_2SO_4$ comparing the data sets of Giaques and Cox.
    - Figure 18: Plot of $\log{a^M_{H_2O}}$ vs $\%H_2SO_4$ comparing the data sets of Giaques and Cox with the data from Zeleznick.
