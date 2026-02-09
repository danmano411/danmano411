<!--
**danmano411/danmano411** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

# Hi there, I'm Dan Mano 👋

## HTEM DB Neural Network Project
Building a curated dataset from NREL’s High Throughput Experimental Materials Database (HTEM DB) and training a neural network to predict thin-film properties (starting with thickness). The project is structured in three stages:

- [x] **Stage 1 — Dataset pipeline (complete):**  
  Notebook-driven workflow to search HTEM libraries, download filtered libraries locally to reduce API calls, and construct a flattened ML-ready dataset (deposition parameters + composition + measurement outputs). Includes preliminary cleaning, EDA, and outlier handling.

- [ ] **Stage 2 — Neural network modeling (in progress):**  
  Training and refining a PyTorch regression model.
  Current focus:
  - Simplify architecture while preserving performance (parameter efficiency vs. accuracy)
  - Tune batch size / learning rate tradeoffs; improve training stability
  - Add regularization (dropout, weight decay) and compare impact on overfitting
  - Implement learning-rate scheduling and early stopping
 
- [ ] **Stage 3 — Web interface (planned):**  
  A lightweight web app for model access and inference once the training pipeline is finalized.

**Repo structure**
- `notebooks/` — HTEM querying, filtering, dataset creation, EDA  
- `neuralnet/` — PyTorch training code and experiments  
- `config/` — local `config.yaml` (ignored by git) for system-specific paths  

**HTEM API:** https://htem.nrel.gov/api-docs

## Repositories I've Contributed To
- Pebble (https://github.com/Vision84/Pebble)
- Parky (https://github.com/Plate1/Parky)
