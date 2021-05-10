## [Radiomic Analysis of Soft Tissues Sarcomas Can Distinguish Intermediate From High-Grade Lesions](https://onlinelibrary.wiley.com/doi/full/10.1002/jmri.25791)

Radiomics paper with only 19 patients to distinguish high grade (14) from intermediate grade (5). They split 60-30-10 for training-validation-test. From diffusion-weighted MRI 65 radiomics features were extracted, all displayed in table 3, but roughly focussing on two classes, intensity-based features and texture features. Next, sequential forward floating search (SFFS) was used to identify the best subset of features. They use SMOTE to oversample the minority class, introducing synthetic examples for training. Classification was performed by a k-nearest neighbor classifier. They report good accuracy for distinguishing intermediate from high grade STS.

#### Notes

- The experimental setup of this paper seems fine, I just don't believe 19 patients will ever be enough to do such experiments.