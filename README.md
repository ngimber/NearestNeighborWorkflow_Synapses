# NearestNeighborWorkflow_Synapses

==========

The included scripts were used to calculate the nearest neighbor (NN) distribution for SynCAM/MPP2/PSD-95 in hippocampal synapses.
The work was published in PLOS Biology and biRxiv: https://doi.org/10.1101/2020.05.29.123034 [2]. A detailled methodical description can be found in both articles.

- "kNearestNeighborOnAvirisSurfaces_batch_v3.py" can be used to calculate NN distributions from distance maps exported from Arivis3D.
- "NN_GenerateRandomizedSynapticDistribution.ipynb" generates a randomized control for the NN distribution by simulating the random distribution from all three proteins on a synaptic surface (e.g. SynCAM) or synaptic lumen (e.g. MPP2 and PSD-95).


References
-------
[2] Schmerl, B., et al., The postsynaptic MAGUK scaffold protein MPP2 organises a distinct interactome that incorporates GABAA receptors at the periphery of excitatory synapses. biRxiv, 2021. https://doi.org/10.1101/2020.05.29.123034
