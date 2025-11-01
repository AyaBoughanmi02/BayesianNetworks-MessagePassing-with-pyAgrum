# BayesianNetworks-MessagePassing-with-pyAgrum
Message Propagation in Bayesian Networks. A practice project analyzing message passing algorithms  in both singly and multiply connected BNs using Python and pyAgrum.

# 🧠 Message Propagation in Bayesian Networks (ReseauxBayesiens)

This repository contains a practice project for a Graphical Models course, focusing on the core principles of **message propagation**  used to perform inference in Bayesian Networks.


## Key Topics Covered

The notebook explores the fundamental difference in inference techniques required for various network structures:

1.  **Singly Connected Networks (Polytrees):** Demonstrates the efficiency of the belief propagation, where messages only need to be passed once without cycles.
2.  **Multiply Connected Networks (Graphs with Cycles):** Illustrates the necessity of more complex algorithms, typically the **Junction Tree Algorithm **, to handle cycles and ensure correct inference.

## 🛠️ Technology and Libraries

* **Python**
* **Jupyter Notebook**
* **pyAgrum:** A powerful Python library for Bayesian Networks and related algorithms (used for modeling and inference).
