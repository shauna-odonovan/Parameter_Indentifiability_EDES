# Parameter Indentifiability: Personalising the Eindhoven Diabetes Education Simulator
Tutorial on parameter uniqueness/identifiability as part of the VITAL Training School 1, Delft University of Technology. 


Shauna O'Donovan and Max de Rooij

Computational models are a valuable tool to study dynamic interactions and the evolution of systems behavior. Our hands-on and interactive workshop will demonstrate how personalized models can be more rapidly generated in Julia using various SciML packages combined with custom implementations. We will cover the implementation of ODE models in Julia, parameter estimation and model selection strategies including parameter sensitivity and identifiability analysis.

Computational models offer a valuable tool for understanding the dynamic interactions between different biological entities, especially in biomedical applications. Personalizing these models with data can shed light on interindividual variation and project future health risks. However, for model parameters to be meaningful and useful for interpretation it is important that they can be accuractely identifed from available data. Our hands-on and interactive workshop will demonstrate how personalized models can be more rapidly generated in Julia. We will be mainly using DifferentialEquations.jl combined with Optimization.jl. We will use an in-house model of the glucose-insulin system (Eindhoven Diabetes Education Simulator) we will breifly cover the implementation and resolving of ODE systems in Julia. We will provide a guide on performing identifiability analysis using inbuilt Julia packages such as StructuralIdentifiabilty.jl and a implementation of Profile Likelhood Analysis with a variable step. For Matlab users and implementation of the model and PLA algorithm can also be provided in Matlab. Short presentation will be used to provide necessary background and theory and all methods will be implemented in a Jupyter notebook to facilitate independent learning.

# Contents
During the workshop, we will address the following elements of dynamic modelling in (systems) biology:

Implementation and simulation of (biological) dynamic models using DifferentialEquations.jl
Parameter estimation
Parameter identifiability analysis with profile likelihood

# Program
The workshop starts with a short introductory presentation, outlining the releavnce of the gluocse-insulin system in maintaining metabolic resilence, the Eindhoven Diabetes Education Simulator (EDES), a computational model of the glucose-insulin system that has been shown to capture relevant features of metabolic resilence from measures time series of glcuose and insulin. The workshop will then explain the principles of parameter identifiablity and provide hands on experience using in-built Julia packages for determining parameter identifiability and an inplementation of the Profile Liklihood Analysis methods proposed by Raue et al.

A. Raue, C. Kreutz, T. Maiwald, J. Bachmann, M. Schilling, U. Klingmüller, J. Timmer, Structural and practical identifiability analysis of partially observed dynamical models by exploiting the profile likelihood, Bioinformatics, Volume 25, Issue 15, August 2009, Pages 1923–1929, https://doi.org/10.1093/bioinformatics/btp358
