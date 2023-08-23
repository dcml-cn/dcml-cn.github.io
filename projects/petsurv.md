## Survival Analysis and Treatment Response Prediction from PET Images

[Back to the main page](https://dcml-cn.github.io/)

### Graph Neural Networks for survival analysis

<img src="../images/graphsurv.png"/>

We propose multi-lesion graphs to caracterise full-body PET images of diffuse large-B-cell lymphoma (DLBCL) patients, instead of single lesion or full image approaches, graphs explicitely model the varibilities in size and number of lesions. Relying on a Graph-Attention-Network (GAT) on top of the multi-lesion attributed graph, and based on a prospective dataset of more than 500 patients, we provide estimages for the 2-year progression free survival of DLBCL patients[[1]](#isbi2023). We have further adapted and extended this approach with a *multi-modal self-attention* block to integrate clinical tabular data within the prediction[^ai4treat2023]

[^ai4treat2023]: otherref


<a id="isbi2023">[1]</a> 
Dijkstra, E. W. (1968). 
Go to statement considered harmful. 
Communications of the ACM, 11(3), 147-148.

---
### Deep Learning and self-supervised learning 

<img src="images/deep_surv"/>

Study of existing and new formulations of the survival cost function to train the network and the proposition of self-supervised pretraining strategies to cope with the database size\footnote{Journal under review and \bibentry{morvan2020learned}}. These results of these two types of methods were the outcome of Ludivine Morvan Ph.D. (2018-2021).  We have also considered a full-body PET imaging approach, which does not require lesion segmentation\footnote{\bibentry{nguyen2022mic}}  in the context of Khac Lan's postdoc (2021-2022).

As a byproduct of the above results, we have started a collaboration for the PET image analysis of  cardiovascular applications.  Recently,  the results of Gauthier Frecon (engineer, 2021-2022) in this direction, have been published in \footnote{\bibentry{godefroy2023jacc}}.

<img src="../images/multitask_pet.png"/>

--
### Machine Learning Frameworks

Based on a classical processing of feature extraction from tumor regions in the images followed by a random survival forest for the prognosis predictions. The main technical contribution of this work is the conception of an unified machine learning framework  capable of automatic feature and model selection to optimize the risk predictions. This work was among the first in combining patient and PET image data for prognosis prediction in the context of multiple myeloma, and to link quantitative features(radiomics) to the risk for multiple myeloma [1]. The benefits were further demonstrated on two prospective clinical datasets\footnote{\bibentry{jamet2020random}}. 

[1] Leveraging Random Survial Forest and PET images for prognosis of multiple myeloma at diagnosis.
Ludivine Morvan, Thomas Carlier, Bastien Jamet, Clément Bailly, Caroline Bodet-Milin, Philippe Moreau,
Francoise Kraeber-Bodéré, and Diana Mateus. 
Int. journal of computer assisted radiology and surgery (IJCARS 2019)

[2]
