# CDL 2021

## Day 1 Exercises

### Set Partitioning exercise
Once a QUBO is mathematically defined it can be programmatically constructed and solved on
a QPU or hybrid solver. This exercise shows you how to define a QUBO dictionary for a mathematical 
model. You will
1. Add the linear and quadratic biases to the QUBO dictionary
2. Run the problem and observe the results

For reference, see slide 46 in the Intro to QUBOs slide deck

### Maximum cut exercise
Now that you have worked through the QUBO formulation in the maximum cut problem,
it's time to program it. In this exercise you will 
1. Build the QUBO dictionary for the maximum cut problem on the graph below 
2. Define a QPU sampler
3. Submit the problem to the sampler

![graphs](readme_images/graph.png "graph")

Here are some resources to get you started:
* Using the QPU sampler (DWaveSampler): https://docs.ocean.dwavesys.com/en/latest/docs_system/reference/samplers.html#dwavesampler
* Embedding a problem onto the QPU (EmbeddingComposite): https://docs.ocean.dwavesys.com/en/latest/docs_system/reference/composites.html#embeddingcomposite
* Observing a solution with the Inspector (using .show()): https://docs.ocean.dwavesys.com/en/latest/docs_inspector/reference/show.html#functions

For reference see the maximum cut solution slides with the problem formulation