# Differential Privacy GAN


This is the report for DPGAN (Xie et al, 2018) where the paper and the most important experiments are replicated. This code does not take any code from the Github - Repo
of the authors. It is much more understandable and helps other readers to understand the paper.

From neuronal networks the training data can be partially reconstructed. (so-called Membership - Attack) 
Often GANs are used to increase new data in difficult to create data sets. A Membership - Attack
is especially a problem if the training data is sensitive. This applies for example to datasets with
rare medical diseases, where one could infer individual patients.

Differential Privacy attempts to provide greater privacy by guaranteeing that the data cannot be traced back to the actual patient and the data cannot be used to infer the actual data. For example, by slightly modifying the data, any patient can be 
patient can infer that he was not part of the input data, but that this was due to random noise. This is called
Plausible Denialbility. 

By using different concepts DPGAN tries to provide privacy guarantes while still creating data.

Unfortunately, the paper is not completely reproducible. Esspecially it was hard to recreate the noisy data.


## Technologies

- Pytorch
- Pytorch Lightning
- Sklearn
- Pandas
- Plotnine


## Packages

- python=3.9
- torch == 1.13.1
- pytorch-lightning = 1.8
- lightning_bolts = 0.6.0
- matplotlib = 3.7
- scikit-learn = 1.2.1
- pandas = 1.5.1
- plotnine = 0.10.1

## Setup


All experiments were done in Report.ipynb.




## Sources


- Xie, Liyang et al. “Differentially Private Generative Adversarial Network.” ArXiv abs/1802.06739 (2018)



