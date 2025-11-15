# Predicting Neural Activity

This project aimed at comparing different approaches for prediction of neural recordings from the InferoTemporal cortex from the stimulus images, in order to identify the best approaches to achieve maximal performance. Particularly, we explored data-driven and task-driven approaches. This project was part of the course NX 414/ Brian-like Intelligence.

## Data

This analysis was performed using the data from the paper of Majaj et al. (10.1523/JNEUROSCI.5181-14.2015), which analyzes neural recordings in the Inferior Temporal cortex from participants looking at images. Their approach models how simple model activations can account for human behavior.

## Task-driven approach

We used models trained for classification of images as task-driven for our framework. We used the activations of the different layers of these task-driven models as input for predicting the neural activations.

We used top-performing models from the Brain Score (https://www.brain-score.org/) platform, assessing the brain alignement performance of the best task-driven classification models.

## Data-driven approach

We directly trained predictive models on the data, comparing simple ridge regression and Convolutionak Neural Networks.

# Acknowledgments

This work was performed with SobhanNili and Laz4rz, and supervised by A. Marin Vargas.