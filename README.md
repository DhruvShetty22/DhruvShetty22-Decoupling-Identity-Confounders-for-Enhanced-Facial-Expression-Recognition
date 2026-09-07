# DICE-FER: Identity-Agnostic Facial Expression Recognition

Implemented **DICE-FER** for identity-agnostic facial expression recognition using **disentangled representation learning**.

## Key Features

* Curated a custom dataset of **1.8K+ facial images**, preprocessing and clustering **22 identities** using **MTCNN** and **KMeans**.
* Extracted facial embeddings using **ResNet-18**, which served as input to the expression and identity disentanglement modules.
* Trained separate **expression and identity encoders** using **mutual information maximization** and **adversarial loss minimization**.
* Achieved **97% classification accuracy**, with strong representation separation validated through **t-SNE visualization** and high **Mutual Information Gap (MIG)** scores.

