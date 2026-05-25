%![PhyOrg](PhysOrg.png)
# Extreme Ester Hydrolysis
As we explore physical organic chemistry we can investigate seemingly simple reactions and observe surprising complexity. This webbook is a collection of documents and data analysis exploring the acid hydrolysis of esters. There are several possible mechanisms that can consume the starting material depending on the structure of the ester and the strength of the acidic conditions. We will be considering acid mixtures far beyond where the pH scale has meaning. Lets get extreme, together. 

## Contents

I wrote a series of explorations of my ideas and work so that I could easily return to my thoughts after setting this aside for any amount of time.

### [Discussion of Yates \& McClellan, 1967](01_Yates1967.md)

I first began this line of thought after reading "Mechanisms of ester hydrolysis in aqueous sulfuric acids." K. Yates, R.A. McClelland, *J. Am. Chem. Soc.*, **1967**, *89*, 2686-2692. https://doi.org/10.1021/ja00987a033

This paper presents a complicated relationship between reactivity and acidity. It also provides evidence supporting an idea that ester hydrolysis is second-order in water. I worked through the data in the paper and present an analysis of the results for methyl acetate in the [documents presented in this page](01_Yates1967.md). The *Python* notebooks can easily be changed to explore the results of the other esters presented in this paper.

### [Interpolating Data](02_interpolating.md)

I wanted to analyze the data using data sets for $H_0$ and $a_{H_2O}$ from sources other that the values reported in Yates \& McClellan, 1967. If the values in a data set did not align with those used by the authors then we will need to use interpolation to estimate the values in the spaces between data points. [This page](02_interpolating.md) presents my efforts to understand the interpolation tools availabe in *Python*. 

### [Searching For Data](03_DataQuest.md)

The paper by Yates and McClellan presents some data in its plots that are not present in the tables. The authors present data for ethyl acetate that is from another paper. The experimental results for methyl acetate hydrolysis are missing three points that appear in the plots but not in the table of experimental data. [This page](03_DataQuest.md) presents an account of my efforts to obtain the data that was left out of the paper.

### [Polynomial Models for $a_{H_2O}$ and more](04_ModelsForaH2O.md)

There are many empirical mathematical models available in the literature for predicting values of density, water activity and acidity of water/acid mixtures. Most of the data tables that I have used so far are the output of these models, not experimental data. To further understand this approach I attempted to use some literature models and compare that to simple polynomial fits through the data. In the end, the best way to use the data tables was concluded to be using a spline interpolation of the data tables. [This page](04_ModelsForaH2O.md) presents my own attempts at modelling the data with the accompanying plots and figures.



