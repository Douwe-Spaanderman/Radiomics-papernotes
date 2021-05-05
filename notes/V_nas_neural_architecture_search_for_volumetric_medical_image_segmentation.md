## [V-NAS: Neural Architecture Search for Volumetric Medical Image Segmentation](https://arxiv.org/abs/1906.02817)

Neural Architecture Search (NAS) paper which focusses on utilizing various fully convolutional networks (2D, 3D and pseudo-3D) in one network by automatically learning which convolution to select at each layer in the context of a UNet (encoder-decoder) architecture in order to improve segmentation of volumetric medical images. By doing so, both advantages and disadvantage of each type of layer can be balanced, e.g. 3D while being more informative on spatial relationship along the z-axis requires a lot more computing power. In order to train this model weights are trained for 20 epochs on training set. Next loss function is minimized by updating the parameters for each encoder and decoder layer. Lastly, these parameters are maximized to select one of the three (2D, 3D and pseudo-3D) for each layer and weights are retrained for the whole train+validation set. Together, this paper provides a novel way of applying autoML to medical imaging, improving current state-of-the-art.

#### Notes

- Very cool NAS paper, with very promosing results for automated segmentaion of medical images.
- The switching between 2D, 3D and pseudo 3D seems interesting
- I don't completly agree with their generalizability statement as for each dataset the V-NAS search has to be done to outperform state of the art, this could possible still lead to overfitting. Also hinted towards by the lack of consistency, in my eyes, for the same network structure, i.e. selected layer types, between datasets.
- Disadvantage of 3D was the large number of parameters required to be trained, however I feel like this should still be a problem as the search space is only increased due to the convolution selection parameter at each layer.
- I would have liked to see additional benchmarks