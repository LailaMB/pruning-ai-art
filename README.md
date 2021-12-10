# Pruning Ai Art
This repository contains a pytorch code for pruning Ai art models. 


![Model Architecture](/samples/yellow_flowers.gif)


## Code

Two notebooks are provided: 
1. Pruning_2D_autoencoder.ipynb: a 2D autoencoder for pruning image artworks.
2. Pruning_3D_autoencoder.ipynb: a 3D voxel autoencoder for pruning sculptures. 

The autoencoder are trained to reconstruct the given artwork. When the train is completed, a gradual pruning of the autoencoder's weights is applied to create minimized and abstract versions of the artwork. 
