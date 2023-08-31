## Spatial continuity and domain adaption for 3D muscle segmentation

[Back to the main page](https://dcml-cn.github.io/)

In this project we aim at segmenting and quantifying the volume of muscles from ultrasound or magnetic resonance volumes. Muscle volume is a biomarker for high-performance athletes and in degenerative musculoskeletal diseases.The main challenge here is the annotation cost, with a manual annotation of a single volume ranging from 5 hours to 1 week according to the number of muscles to segment.  The addressed research question  is how to make accurate predictions with a segmentation deep neural network trained with few subjects and sparse annotations.  Our main contributions involve learning from incomplete annotations\footnote{\bibentry{duque2020spatio}} and adding a "spatio-temporal" modeling  between 2D slices of the same volume \footnote{\bibentry{alchanti2021ultrasound}}.
We have also started investigating to transfer the knowledge across imaging modalities \footnote{\bibentry{dawood2021olva}}. These are the main results of the Vanessa Gonzalez-Duque (Ph.D. candidate) and Dawood Al Chanti (postdoc, now MdC).  Louise Piecuch,  engineer,  has extended the above approaches to consider 20 muscles simultaneously (instead of 3) and explores the use of Transformers with very promising results.

This work is done in collaboration with the MIP lab/STAPS  in Nantes. 

* Vanessa Gonzalez-Duque, Dawood Al-Chanti, Marion Crouzier, Antoine Nordez, Lilian Lacourpaille, and Diana Mateus.
Spatio-temporal consistency and negative label transfer for 3d freehand us segmentation. In International Conference
on Medical Image Computing and Computer Assisted Interventions (MICCAI), pages 710–720. Springer, October 2020

* Dawood Al Chanti, Vanessa Gonzalez-Duque, Marion Crouzier, Antoine Nordez, Lilian Lacourpaille, and Diana Mateus.
IFSS-Net: interactive few-shot siamese network for faster muscle segmentation and propagation in volumetric ultrasound.
IEEE Transactions on Medical Imaging (TMI), February 2021. (JCR)

* Dawood Al Chanti and Diana Mateus. Olva: Optimal latent vector alignment for unsupervised domain adaptation in
medical image segmentation. In International Conference on Medical Image Computing and Computer Assisted Interventions
(MICCAI), pages 261–271. Springer, 2021

  DOI: https://doi.org/10.1007/978-3-030-87199-4_25
  
  [SharedIt:](https://rdcu.be/cyl38)
  
  [Link to the code repository](https://github.com/DawoodChanti/OLVA)

  [Link to the dataset(s)](https://zmiclab.github.io/projects/mmwhs/)
