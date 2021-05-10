## [Supervised Contrastive Learning](https://arxiv.org/abs/2004.11362)

This paper reports a new loss function, supervised contrastive learning (SupCon), for (self-)supervised learning which outperforms cross-entropy on large-scale datasets such as ImageNet. SupCon utilizes the common idea to pull together an anchor and positive samples, while pushing apart the anchor from negative samples in the embedding space. In a self-supervised environment, the anchor could be the original image and positive samples would be the augmentation of this image. Next negative samples would be any other randomly selected imaging data, which hopefully doesn't contain any false positives. The supervised approaches additionally uses the label of the data in order to match anchor and positive/negative samples. Afterwards, for classification, a linear classifier can be trained on top of this frozen representation learned traditionally with a cross-entropy loss. They assess there loss function in different setting, with various datasets, augmentation algorithms and ResNet architectures.

#### Notes

- Very interesting paper!
- Cross entropy has drawbacks such as sensitivity to noise labels, presence of adversarial examples and poor margins.