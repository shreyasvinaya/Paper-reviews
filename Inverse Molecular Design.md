# Inverse molecular design using machine learning: Generative models for matter engineering

**Aim** review methods for achieving inverse design, which aims to discover tailored materials from the starting point of a particular desired functionality

## What is the paper trying to solve:
The paper is trying to address the challenge of efficiently searching the vast space of possible molecular and solid-state compounds, known as chemical space, in order to discover new materials that have desired properties and functionalities. This goal is referred to as inverse molecular design.
The size of chemical space is enormous (on the order of 10^60 molecules for drug-like compounds alone), making exhaustive search intractable. The traditional forward approach starts with a chemical structure and predicts its properties, but this is inefficient for finding optimal materials. Inverse design inverts this process to start with target properties and find optimal structures.

## Methodology used
The paper reviews several machine learning approaches for inverse molecular design:
- **High-throughput virtual screening (HTVS)** - Screens large virtual libraries of compounds based on desired criteria. Requires hand-crafted molecule libraries and heuristics.
- **Evolutionary strategies** - Apply heuristics inspired by biological evolution, like mutation and selection, to evolve molecules toward a target.
- **Variational autoencoders (VAEs)** - Learn a continuous latent representation of chemical space. Allows optimization via gradient descent in this space.
- **Reinforcement learning** - Train generative models via rewards for desired properties. Allows guided exploration of chemical space.
- **Generative adversarial networks (GANs)** - Compete a generative model against a discriminative model to better capture the distribution of real molecules.


## My understanding
The key points I took away are:
* Inverse design formulates materials discovery as an optimization problem - start with target property, find optimal structures.
* Machine learning, especially generative models like VAEs and GANs, can help efficiently search and model chemical space.
* These methods allow incorporating existing data to guide search, rather than random or manual exploration.
* Representations that encode relevant molecular properties and relationships are critical for generalization.
* There has been promising progress applying these techniques to discover drug candidates, organic electronics, etc.
* Scaling to larger areas of chemical space and closing the loop with synthesis remains an open challenge.

## Why is it relevant
Inverse design has the potential to greatly accelerate the discovery of new functional materials in a wide range of applications, from drugs to batteries to catalysts. This could help address many technological challenges facing society.

The machine learning approaches surveyed enable more systematic exploration of chemical space than manual approaches based on researcher intuition. They allow exploiting large datasets to guide the search process.

In addition, the generative models provide a flexible way to model chemical space itself for guided sampling. This is more efficient than exhaustive enumeration.

## What are some pitfalls:
* Chemical structures are discrete, making optimization difficult for gradient-based methods.
* Evaluating viability and synthesizability of generated molecules is still a bottleneck.
* Current generative models focus on small drug-like molecules. Expanding to broader chemical space is an open challenge.
* Lack of consistent molecular representations and property prediction methods limits wider application of these techniques.
* Closing the loop with experimental validation and feedback remains difficult.

## References:
[1] Benjamin Sanchez-Lengeling, Alán Aspuru-Guzik ,Inverse molecular design using machine learning: Generative models for matter engineering.Science361,360-365(2018).DOI:10.1126/science.aat2663

