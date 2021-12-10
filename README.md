# Pruning Ai Art
This repository contains the code for pruning Ai art models. 


![Model Architecture](/samples/yellow_flowers.gif)

Two notebooks are provided, one for 2D autoencoder for image artworks and the other for 3D voxel autoencoder for pruning sculptures. The autoencoder is trained to reconstruct the given artwork. When the train is completed, a gradual pruning of the autoencoder weights is applied to create minimized and abstract versions of the artwork. 
