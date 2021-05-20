## [Attention gated networks: Learning to leverage salient regions in medical images](https://www.sciencedirect.com/science/article/pii/S1361841518306133)

Paper which uses attention gates (AG) to append localization information to improve classification and segmentation. Tested in VGG-net for image classification of 2D ultrasound scan and U-net for 3D CT pancreas segmentation, both outperforming 'state-of-the-art'. Noteworthy is that localization information wasn't very useful in earlier layers but AG was useful later on in the network.

#### Notes

- Great paper and interesting for classification
- VGG-net is probably not gonna cut it as 'state-of-the-art' -> but AG can be used in any CNN.