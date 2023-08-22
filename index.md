
<img src="images/milcom-logos.png?raw=true"/>
## Multimodal Imaging and Learning for Computional-based Medicine

My research activities center around medical image analysis through signal processing, machine learning, and computer vision techniques. 
Since 2018 I have been the holder of the MILCOM (Medical Imaging and Learning for COmputationally based Medicine) Chair. This project aims to design machine-learning methods that explicitly consider the challenges of medical imaging data. These challenges include dealing with large volumes,  multi-modal and heterogenous data,  small and imbalanced databases, and/or limited access to expert annotations. Formalizing the learning process under such conditions has been declined in three different directions within the context of three interdisciplinary collaborations. 
---

### Survival Analysis, PET images and Machine Learning 

This project points to the development of machine learning algorithms to assist the diagnosis and personalized treatment of patients suffering from hematological diseases such as multiple myeloma or diffuse large B-cell lymphoma (DLBCL) patients. In particular, we aim to *predict a patient's prognosis or treatment response given their full-body PET images*, possibly combined with clinical data. To this end, we have proposed several types of approaches: 

In a more recent approach, we replace the feature extraction step with learned radiomics from a neural network. In this case, the technical contribution comes from the study of existing and new formulations of the survival cost function to train the network and the proposition of self-supervised pretraining strategies to cope with the database size\footnote{Journal under review and \bibentry{morvan2020learned}}. These results of these two types of methods were the outcome of Ludivine Morvan Ph.D. (2018-2021).  We have also considered a full-body PET imaging approach, which does not require lesion segmentation\footnote{\bibentry{nguyen2022mic}}  in the context of Khac Lan's postdoc (2021-2022).  A new PhD,  Oriane Thiery (2022-2025),  will continue to develop this axis by considering patient and population graphs.

As a byproduct of the above results, we have started a new collaboration based on PET image analysis for a cardiovascular application.  Recently,  the results of Gauthier Frecon (engineer, 2021-2022) in this direction, have been published in a top journal of the application field\footnote{\bibentry{godefroy2023jacc}}.

[Graph-based survival learning](/sample_page)
<br>
We propose multi-lesion graphs as an original solution to caracterise full-body PET images of large-B-cell diffuse lymphoma patients, instead of single lesion or full image approaches, graphs explicitely model the varibilities in size and number of lesions. Relying on a Graph-Attention-Network (GAT) on top of the multi-lesion attributed graph, and based on a prospective dataset of more than 500 patients, we provide results for the 
<img src="images/dummy_thumbnail.jpg?raw=true"/>

---
[Self-supervised learning](/pdf/sample_presentation.pdf)
<img src="images/dummy_thumbnail.jpg?raw=true"/>

---
[Random Survival Forests Framework](http://example.com/)
<img src="images/dummy_thumbnail.jpg?raw=true"/>
Based on a classical processing of feature extraction from tumor regions in the images followed by a random survival forest for the prognosis predictions. The main technical contribution of this work is the conception of an unified machine learning framework  capable of automatic feature and model selection to optimize the risk predictions. This work was among the first in combining patient and PET image data for prognosis prediction in the context of multiple myeloma, and to link quantitative features(radiomics) to the risk for multiple myeloma [1]. The benefits were further demonstrated on two prospective clinical datasets\footnote{\bibentry{jamet2020random}}. 

[1]
[2]

---
### Image Reconstruction and Learning

[Project 3 Title](http://example.com/)
<img src="images/dummy_thumbnail.jpg?raw=true"/>

---
### Learning with small datasets and few annotations

[Project 3 Title](http://example.com/)
<img src="images/dummy_thumbnail.jpg?raw=true"/>

---

### Industrial Collaborations

- [HERAMI](http://example.com/)
- [KEOSYS](http://example.com/)

---




---
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
