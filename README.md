Enhancing Dangerous Scene Classification with
Multimodal LLMs and Attention Mechanisms

#Quick start
!git clone https://github.com/YourUsername/Gemini-Scene.git

#1. Experimental Environment

This code is intended to run on Google Colab for maximum convenience and rapid debugging.
The open-source release includes:

The main classification model

All ablation-study variants

The dataset construction scripts

The raw dataset archive

#2. Reproducing the Paper’s Results

We’ve added detailed explanations to every section of the notebooks so you can follow our workflow step by step.
Simply run each cell from top to bottom in the following order:

Dataset setup & preprocessing

Open and execute dataset_method.ipynb to build and preprocess the dataset.

Model training & evaluation

Open and execute Main_Model+Ablation_model.ipynb to train the main model and all ablation variants.
Review inline metrics (accuracy, F1 score) and visualizations (loss curves, attention maps).

By following this sequence, you will fully reproduce the experiments and results reported in our paper!
