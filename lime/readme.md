# LIME explained and experiments

These notebooks give an explaination for LIME and variates the method made in [^2].
For both experiments we used a Resnet-50 computer vision. Our goal was finding the most important areas for an explaination. 
In *lime_explained_imagenet.ipynb* we will use a grid based approach for LIME instead a superpixel.
In *lime_owned_data.ipynb* we will discuss lime on the data set *Architectural_Heritage_Elements_Dataset_128*.



## Technologies

- Pytorch
- Scikit-Learn
- Numpy



## Packages

- python=3.9
- pytorch=1.13
- matplotlib=3.7
- scikit-image=0.19.3
- scikit-learn=1.2.1


## Setup

You can view *lime_explained_imagenet.ipynb* and *lime_owned_data.ipynb*  for the results.


## Sources

[^1] Ribeiro, Marco Tulio et al. “"Why Should I Trust You?": Explaining the Predictions of Any Classifier.” Proceedings of the 22nd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining (2016): n. pag.
[^2] Artega, Christian: "Interpretable Machine Learning with LIME for Image Classification". https://nbviewer.org/url/arteagac.github.io/blog/lime_image.ipynb

