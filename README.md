# Prototype Discriminative Learning for Semi-Supervised Change Detection in Remote Sensing Images

This project contains the implementation of our work for change detection:
`Prototype Discriminative Learning for Semi-Supervised Change Detection in Remote Sensing Images`

## News
Repo is created in 2023-07-14. Code will come soon.

## Abstract
With the development of deep learning in remote sensing  (RS) visual tasks, RS image change detection (CD) has achieved remarkable progress. 
However, existing CD methods rely heavily on large volumes of fully pixel-wise hand-annotated training data which is a time-consuming and costly process, 
and they fail to take full advantage of helpful deep feature representations in the deep feature domain. 
To address the above issues, A novel semi-supervised CD method based on prototype discriminative learning (PDL) is proposed to adequately exploit useful information in massive unlabeled data as a supplement to the labeled data. 
Specifically, changed objects and unchanged backgrounds are complex and variable, our approach encourages dividing each category into multiple sub-classes in the deep feature domain, 
with the feature distribution of each sub-class obeying a Gaussian distribution. Then, prototype discriminative learning explicitly encourages features of samples closer to the nearest prototype in the category they belong to and away from all prototypes of other categories, 
which is achieved by feature discriminative loss (FDL) designed to construct more pronounced intra-class compactness and inter-class variability. 
Extensive comparative experiments conducted on three available and widely used change detection datasets demonstrate that our proposed semi-supervised CD method achieves better CD performance than recent counterparts.
