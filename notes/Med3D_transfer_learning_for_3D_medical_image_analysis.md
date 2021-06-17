## [Med3D Transfer Learning for 3D Medical Image Analysis](https://arxiv.org/abs/1904.00625)

Very interesting paper of creating a pooled dataset of different modalities (MRI/CT), application (brain, hearth, prostate, etc.) and multi-center, using it to do transfer learning to other medical application. Important is the use of spatial normalization and intensity normalization as images are going to be very different, also interesting that MRI and CT are mixed here. Next, normalized cropped regions or whole image, are used to train the Med3D network, which uses a ResNet structure backbone and a different architecture depending on the tasks, i.e. for segmentation fully connected layers (normally in ResNet) are replaced with a 8-branch decoder (with 1x1x1 + upsampling). Aside from the pooled dataset, Med3D is assessed on lung segmentation, Pulmonary nodule classification and LiTS challenge (segmentation of liver and liver tumors).

#### Notes

- Really interesting paper
- Spatial normalization and intensity normalization very important methods
- Transfer learning seems cool, can we try something here
- More open data a better working Med3D

#### Keywords

CNN | Deep Learning | 3D | DenseNet | Segmentation | Classification | Medical | MRI | CT | Transfer Learning | Multi-center | ResNet