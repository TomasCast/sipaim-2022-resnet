# A ResNet is All You Need? Modeling A Strong Baseline for Detecting Referable Diabetic Retinopathy in Fundus Images

## 1. Readme

This repository accompanies our SIPAIM 2022 article on referable diabetic retinopathy detection in fundus images using a ResNet-18 model.

You will find here a series of files and resources that might help you to train your own models under the same setting than ours, in an effort to improve the way we compare methods for this task. Hence, we provide you with:

* A series of ```.ini``` files with our partitions in training, validation and test based on multiple public databases. This includes a separation of the original EyePACS training set into training and validation.
* A ```.csv``` file with our predictions for validation and test images. This includes the non-referable / referable DR probabilities for each of the images, that might be used for you e.g. to generate your own ROC curves.

## 2. Citation

If you use any of these resources, please cite the following article:

```
@inproceedings{castilla2022resnet,
  title={A ResNet is All You Need? Modeling A Strong Baseline for Detecting Referable Diabetic Retinopathy in Fundus Images},
  author={Castilla, Tom{\'a}s and Mart{\'i}nez, Marcela S and Legu{\'i}a, Mercedes and Larrabide, Ignacio and Orlando, Jos{\'e} Ignacio},
  booktitle={18th International Symposium on Medical Information Processing and Analysis, SIPAIM 2022},
  year={2022},
  publisher={SPIE}
}
```