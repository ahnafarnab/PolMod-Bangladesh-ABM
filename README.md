# PolMod-Bangladesh-ABM
This repository contains the reproducible codes for my agent-based model on hybrid regimes and liberal decay (2023/2025).
============================================================================================================

The PolMod-Bangladesh-ABM is an extension of my Master's project. As an advocate of open-source data, all data preprocessing, modeling, simulation, and analysis conducted for this study are fully reproducible and implemented in Python via the MESA 3.3.1 framework. This repo contains the complete codebase — including the agent-based model (PolMod), simulation routines, Monte Carlo experiments, neural-network–augmented agents, and visualization scripts.\

It is structured in the following manner -\

  • data/ –            Anonymized and processed survey data of 399 agents or leaders across Bangladeshi political                           parties (BAL, BNP, CPB, BASOD, Jamaat).\
  • model/ –           The core ABM logic, agent rules, network interactions, and decay/shock mechanisms.\
  • nn/ –              Neural-network extensions and learning routines or backpropagation.\
  • analysis/ –        Statistical tests and experiments, including - entropy measures, Lyapunov exponent                                   estimation, power-law fits, Granger causality, and DiD analysis.\
  • figures/ –         Scripts and PNG files to reproduce all figures and tables in the manuscript.\
  • notebooks/ –       Jupyter notebooks for step-by-step replication of results.\
  • requirements.txt – The exact package dependencies and versions.\
