## Neural Networks and Image Reconstruction

[Back to the main page](https://dcml-cn.github.io/)

### Graph Neural Networks for survival analysis
*PhD Candidates:* 
  Younes Moussaoui (2022-2025) - Funded by: ????
  M"ael Millardet (2018-2021) - Funded by: MILCOM Chair
*Master student:* Hernan Carillo (2020) - Funded by: MILCOM Chair

<img src="../images/deepreco.png"/>

We propose multi-lesion graphs to caracterise full-body PET images of diffuse large-B-cell lymphoma (DLBCL) patients, instead of single lesion or full image approaches, graphs explicitely model the varibilities in size and number of lesions. Relying on a Graph-Attention-Network (GAT) on top of the multi-lesion attributed graph, and based on a prospective dataset of more than 500 patients, we provide estimages for the 2-year progression free survival of DLBCL patients [[ISBI2023]](#isbi2023). We have further adapted and extended this approach with a *multi-modal self-attention* block to integrate clinical tabular data within the prediction [[AI4Treat@MICCAI2023]](#ai4treat2023)


* <a id="ai4treat2023">[AI4Treat@MICCAI2023]</a>
6. Maël Millardet, Said Moussaoui, Diana Mateus, Jérôme Idier, and Thomas Carlier. Local-mean preserving postprocessing
step for non-negativity enforcement in pet imaging: application to 90y-pet. IEEE Transactions on Medical Imaging
(TMI), 39(11):3725–3736, 2020. (JCR)
7. Mäel Millardet, Säid Moussaoui, Jérôme Idier, Diana Mateus, Maurizio Conti, Clément Bailly, Simon Stute, and
Thomas Carlier. A multi-objective comparative analysis of reconstruction algorithms in the context of low-statistics 90YPET
imaging. IEEE Transactions on Radiation and Plasma Medical Sciences, 2021. (Web of Science Core Collection:
Emerging Sources Citation Index)
8. Hernan Carrillo, Maël Millardet, Thomas Carlier, and Diana Mateus. Low-count PET image reconstruction with
Bayesian inference over a Deep Prior. In Ivana Išgum and Bennett A. Landman, editors, Medical Imaging: Image Processing,
volume 11596, pages 227 – 235. International Society for Optics and Photonics, SPIE, 2021,Alexandre Merasli, T. Liu,
Thomas Carlier, Diana Mateus, Mael Millardet, Said Moussaoui, and Simon Stute. Nested admm for pet reconstruction with
two constraints : Deep image prior and non-negativity in projection space. In IEEE Nuclear Science Symposium, Medical
Imaging Conference, November 2022


