# GAMLj: The GLM module for Jamovi

General Linear Model module of the GAMLj suite for Jamovi

The module estimates a general linear model with categorial and/or continuous variables, with options to facilitate estimation of 
interactions, simple slopes, simple effects, etc.

You will first need to download [Jamovi](https://www.jamovi.org/download.html). 

Detailed information at  https://mcfanda.github.io/gamlj_glm/

<img src="docs/i1.png" class="img-responsive" alt="">



## Model
The module can estimate OLS linear models for any combination of categorical and continuous variables, thus providing an easy way for multiple regression, ANOVA, ANCOVA and moderation analysis. 
## Estimates
The modules provides ANOVA tables and parameter estimates for any estimated model. Effect size (eta, omega, and beta) are optionally computed

## Variable Scaling
Within the module, by simply point-and-click, categorial variable can be coded in many different ways, as dummies, centered, difference, helmeret, etc.
Continuous variables can be centered, standardized. 

## Post-hocs
For categorical variables, all major post-hoc tests are computed

## Plots
The "plots" menu allows for plotting  main effects and interactions for any combination of types of variables, 
making it easy to plot interaction means plots, simple slopes, and combinations of them. The best plot is chosen automatically.
Plots can plot up to a three-way interaction.
## Simple effects
Simple effects can be computed for any combination of types of variables, 
making it easy to proble interaction, simple slopes, and combinations of them. 
Simple effects can estimated  up to a three-way interaction.

# Installation

You can clone this repository and compile the module within R with 

``` jmvtools::install() ```

or, without cloning anything, just run this within R

```
library("devtools")
install_github("mcfanda/gamlj_glm")
```
