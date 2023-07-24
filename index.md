---
layout: default
---

# About the tutorial

In this tutorial, we are going to demonstrate how we can use machine learning as a practical tool to design self-organizing systems, train emergent patterns to perform desired tasks or achieve predefined goals. These systems are composed of large numbers of locally interacting “microscopic” agents (e.g. grid cells, particles), they work together towards a shared common goal (e.g. matching a target pattern, or surviving in a virtual environment), and form dynamical “macroscopic” patterns that are believed to be performing morphological computation. Such systems are often described as demonstrating self-organization of collective intelligence.

We are going to put emphasis on cases of hierarchical organization of virtual matter, when higher-level structures demonstrate the characteristics of agent-like behavior. Examples include: Neural Cellular Automata (NCA), where self-organizing patterns can be trained using gradient descent and back-propagation-through-time to reproduce a texture or auto-classify symbols, with capabilities of spontaneous regeneration and noise resistance; complex adaptive systems called Lenia, where agent-like localized patterns (or “virtual creatures”) are trained for agent-agent and agent-environment interactions inside a virtual environment; Flow Lenia, where mass conservation law is incorporated into Lenia such that energy constraints and species-species interactions become feasible; and Particle Lenia, where the concept of energy minimization is introduced in Lenia applied to a particle system.

# Materials

## Particle swarm pattern formation demo

[Colab](https://colab.research.google.com/github/SelfOrgML/selforgml.github.io/blob/main/pattern_formation_alife23.ipynb)
[Web Demo](https://znah.net/icra23/)

## Lenia with EvoJAX/Sax demo

### Python libraries

EvoJAX: [github.com/google/evojax](https://github.com/google/evojax)

EvoSax: [github.com/RobertTLange/evosax](https://github.com/RobertTLange/evosax)

### Lenia basics

From Conway to Lenia (with results): [bit.ly/ConwayToLenia](https://bit.ly/ConwayToLenia)

From Conway to Lenia (minimal): [bit.ly/ConwayToLeniaSmall](https://bit.ly/ConwayToLeniaSmall)

### Lenia with gradient descent

Training Sensorimotor Agency: [bit.ly/DiffLenia2](https://bit.ly/DiffLenia2)

### Lenia with evolutionary algorithms

Lenia with JAX: [bit.ly/LeniaJAX](https://bit.ly/LeniaJAX)

Lenia with EvoJAX: [bit.ly/LeniaEvoJAX](https://bit.ly/LeniaEvoJAX)

Flow Lenia: [bit.ly/FlowLenia](https://bit.ly/FlowLenia)

Flow Lenia with EvoSax: [bit.ly/EvoFlow](https://bit.ly/EvoFlow)

# Organizers

[Bert Chan](https://chakazul.github.io/) – Google Research, Brain Tokyo

[Alexander Mordvintsev](https://znah.net/) – Google Research, Zurich

Bert Chan is a Research Engineer in Google Brain Tokyo. His research interests include artificial life and evolutionary computation. He discovered a complex adaptive system called Lenia, for which he received the Outstanding Publication of 2019 award by the International Society for Artificial Life. Bert is also an external collaborator at Inria Bordeaux, and a visiting scholar at the Institute for Advanced Study, Princeton.
Past talks: [Training Sensorimotor Agency in Cellular Automata](https://www.youtube.com/watch?v=FU6BGUwHcg0) at Cohere, 2022

Alexander Mordvintsev is a Research Scientist in Google Zurich. He works on practical methods for self-organizing systems engineering. His recent research focuses on applying differentiable optimization to learn local policies capable of reaching global goals in multiagent systems, like Neural Cellular Automata or Particle Lenia. Previously Alexander worked on analyzing and visualizing deep neural network models and was responsible for creation of the viral DeepDream algorithm.
Past talks: [DeepDream to Neural CA](https://www.youtube.com/watch?v=nSmZBfCO8YE) at SIGGRAPH 2021

# Keywords

neural cellular automata; differentiable programming; self-organizing systems; artificial life; continuous cellular automata; Lenia

# Related past tutorials

[Differentiable Self-Organizing Systems](https://selforglive.github.io/) at ALIFE 2021

[Open Science Project with Lenia](https://openlenia.github.io/) at ALIFE 2021

