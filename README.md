# Kinase_inhibitor_screening
Kinase-inhibitor binding predictor that pairs a graph neural network (GNN-MoE) trained on the Davis dataset with a 12-pathway Tox21 toxicity model on Morgan fingerprints. Includes a Flask web app that reports pKd/Kd/ΔG, toxicity flags, and an interactive 3D pocket view built with RDKit and 3Dmol.js.
