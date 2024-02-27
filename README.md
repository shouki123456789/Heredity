# Heredity
Predict the likelihood of inheriting certain genetic traits within a family. 
## Overview
The Heredity project aims to model the probability distributions of gene inheritance and expression of a trait (e.g., hearing impairment) within a population. It utilizes Bayesian Networks to represent dependencies between genes and traits across family generations.
## Background
Mutated versions of the GJB2 gene are known to be a leading cause of hearing impairment in newborns. Each individual inherits two copies of the gene, and the number of mutated copies can vary. However, the expression of the trait (hearing impairment) might not directly correlate with the number of mutated copies due to additional factors like mutation probabilities.
## Bayesian Network Model
The Bayesian Network model used in this project considers each individual's Gene random variable (representing the number of mutated gene copies) and Trait random variable (indicating the expression of the trait). There are arrows from Gene to Trait variables, indicating that a person's genes influence the probability of exhibiting the trait. Additionally, there are arrows from parents' Gene variables to their child's Gene variable, representing gene inheritance.
## Specification
For more information about the project specifications, please refer to the [Harvard CS50AI](https://cs50.harvard.edu/ai/) website.
Please avoid directly copying the source code as it is provided for reference purposes only. 
