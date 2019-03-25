# Objectives

The objective of this document is to assess the use of various search methods in finding the optimal values of hyperparameters of a machine learning model. The population-based search methods to be tested are genetic algorithms (GA), differential evolution (DE) and particle swarm optimization (PSO). Grid and random search will also be performed and used as benchmarks.

XGBoost with generalized linear models as learners will be used to predict the compressive strength of concrete based on its composition. The compressive strength of concrete is determined  by its age and composition. 

The dataset used comes from the research paper [*Modeling of strength of high performance concrete using artificial neural networks*](https://www.sciencedirect.com/science/article/pii/S0008884698001653) by I-Cheng Yeh published in *Cement and Concrete Research*, Vol. 28, No. 12, pp. 1797-1808 (1998). The dataset can be downloaded through the [UCI Machine learning Repository](http://archive.ics.uci.edu/ml/datasets/Concrete+Compressive+Strength).

The dataset contains 1030 examples and the following features:

* Input Variable: Cement (kg in a m^3^ mixture)
* Input Variable: Blast Furnace Slag (kg in a m^3^ mixture)
* Input Variable: Fly Ash (kg in a m^3^ mixture)
* Input Variable: Water (kg in a m^3^ mixture)
* Input Variable: Superplasticizer (kg in a m^3^ mixture)
* Input Variable: Coarse Aggregate (kg in a m^3^ mixture)
* Input Variable: Fine Aggregate (kg in a m^3^ mixture)
* Input Variable: Age (days)
* Output Variable: Concrete compressive strength (MPa)

The final report can be accessed through [this link](https://rpubs.com/jeandsantos88/search_methods_for_hyperparameter_tuning_in_r)
