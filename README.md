# Techniques for Compressing Pruned Feedforward Neural Networks: A Comparative Study
## Description
We use pruning on trained models and apply PCA, SparsePCA, and FastICA for further compression. Our goal is to create smaller networks that maintain comparable performance to their original, uncompressed versions.

## Installing
You can run the code directly from Google Colab
Ensure that the trained model is saved to your preferred location, which needs to be amended before running the code. 
## Dataset
The dataset is the UCI Online News Popularity dataset, which can be found here https://archive.ics.uci.edu/dataset/332/online+news+popularity
## Pre-trained Model
A pre-trained model is available and does not require re-training for immediate evaluation or application. This model is saved in the folder, trained model. Make sure to reference this location when loading the model in the notebook as the current notebook mounts to my personal google drive. 
## Running the Notebook
To run the notebook effectively, follow these steps:
Ensure all modules listed in the first section of the notebook are installed.
Open the notebook in your preferred environment that supports IPython notebooks (e.g., Jupyter, Google Colab).
The section labeled 'Training and Testing of the Feedford Neural Network' is optional and can be skipped during execution. This section does not influence the overall results and is included for completeness.
Execute the remaining cells in the notebook, which are configured to use the pre-trained model from folder 'trained model' for demonstration or further analysis.
