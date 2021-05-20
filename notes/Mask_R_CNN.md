## [Mask R-CNN](https://arxiv.org/abs/1703.06870)

Facebook paper for object instance segmentation, generating high quality segmentation. This approach extends Faster R-CNN by adding a branch for predicting segmentation masks on each Region of Interest (RoI). This is in parallel with classification and bounding box regression. Just like previous paper, Mask R-CNN the first two stages are proposing candidate object bounding boxes (region proposal network) and RoIPool for each candidate to perform classification and bounding box regression. Additionally, Mask R-CNN outputs a binary mask for each candidate RoI. In contrast to most methods, classification isn't dependent on mask predictions as it is done in parallel. Intuitively, the loss function is a multi-task loss on each sampled RoI, with classification loss, bounding-box loss and a mask loss. For the mask a per pixel sigmoid is conducted and the loss is defined as the average binary cross-entropy on all the pixels in RoI. Noteworthy, is that there is no competition between classes. Mask R-CNN is assessed with different architecture backbones, such as ResNet and Feature Pyramid Network (FPN)

#### Notes

- Of course a great paper for object detection and segmentation
- Applicable to radiomics?

#### Keywords

Methods | Deep learning | Convolution | Classification | Segmentation | R-CNN | Mask | RoI | ResNet | Feature Pyramid Network