---
layout: page
title: Research
order: 2
---

I'm currently working on a diverse set of machine learning projects, including projects related to international trade and the analysis of weather data. Various other projects I've worked on are listed below, organized by application area. My PhD dissertation may be found [here](https://digital.lib.washington.edu/researchworks/bitstream/handle/1773/46581/Jones_washington_0250E_22188.pdf?sequence=1&isAllowed=y).


### Machine learning for neuroscience
Recent advances in 3D microscopy allow for recording the neurons in freely-moving *C. elegans* at high frame rates. In order to be able to study the calcium activity in the neurons, it is necessary to be able to track the individual neurons from frame to frame. Most automated methods proposed in the literature for tracking neurons focus on immobilized or partially-immobilized worms and fail to generalize to the freely-moving-worm setting. In this work we propose methods for automated tracking of neurons in freely-moving worms in the setting where a subset of neurons are marked with red fluorescence.

- Corinne Jones, Mahsa Barzegar Keshteli, Alice Gross, Guillaume Obozinski, and Sahand Jamal Rahi. A Graph Matching Approach to Tracking Neurons in Freely-Moving *C. elegans.* Submitted.  
- Core Francisco Park, Mahsa Barzegar Keshteli, Kseniia Korchagina, Ariane Delrocq, Vladislav Susoy, Corinne Jones, Aravinthan D. T. Samuel, and Sahand Jamal Rahi. Automated neuron tracking inside moving and deforming *C. elegans* using deep learning and targeted augmentation. Accepted at *Nature Methods.*  
[[paper]](https://www.biorxiv.org/content/10.1101/2022.03.15.484536v1) [[code]](https://github.com/rahi-lab/targettrack)  


### Statistical machine learning for any domain
Many papers have focused on achieving the best possible performance in a common domain-specific semi-supervised learning task. In this work we instead introduce approaches to end-to-end learning that allow one to jointly learn feature representations from unlabeled data (with or without labeled data) and learn the labels in a domain-agnostic manner. The proposed approaches can be used on any amount of labeled and unlabeled data, gracefully adjusting to the amount of supervision. 

- Corinne Jones, Vincent Roulet, and Zaid Harchaoui. Discriminative Clustering with Representation Learning with any Ratio of Labeled to Unlabeled Data. *Statistics and Computing*, 2022.  
[[paper]](https://arxiv.org/pdf/1912.12979.pdf) [[poster]](https://cjones6.github.io/public/xsdc_poster.pdf) [[code]](https://github.com/cjones6/xsdc)  
*Winner of the 2020 ASA Computing/Graphics Student Paper [Award](https://community.amstat.org/jointscsg-section/awards/student-paper-competition)* 

- Vincent Roulet, Corinne Jones, and Zaid Harchaoui. A Representation-Focused Training Algorithm for Deep Networks. *IEEE Data Science & Learning Workshop*, 2022.   
[[paper]](https://ieeexplore.ieee.org/document/9820431)

- Corinne Jones and Zaid Harchaoui. End-to-end Learning for Retrospective Change-point Estimation. In *Proceedings of the IEEE
International Workshop on Machine Learning for Signal Processing*, 2020.  
[[paper]](https://ieeexplore.ieee.org/document/9231768) [[code]](https://github.com/cjones6/chpt-learn)

### Statistical machine learning for computer vision
ConvNets are typically viewed as different in essence from kernel-based methods. In this work we show that this is unfounded, both formally and empirically. After providing a systematic framework to translate between ConvNets and convolutional kernel networks (CKNs), we demonstrate that ConvNets and their translations into their more principled counterparts, CKNs, perform similarly on landmark computer vision tasks.

- Corinne Jones, Vincent Roulet, and Zaid Harchaoui. Revisiting Convolutional Neural Networks from the Viewpoint of Kernel-Based Methods. *Journal of Computational and Graphical Statistics*, 32:4, 1237-1247, 2023.  
[[paper]](https://www.tandfonline.com/doi/abs/10.1080/10618600.2022.2163649) [[code]](https://github.com/cjones6/yesweckn)

### Statistical machine learning for marine ecology
Oceanographers at the University of Washington are studying phytoplankton, organisms that are responsible for 50% of the total photosynthesis on Earth. We developed a change-point algorithm that may one day be embedded on board their research vessels to help them adapt their models and data collection in real time. The algorithm will also be used in retrospective analyses. Our work was featured on the UW eScience [website](http://escience.washington.edu/shifts-in-marine-microbial-populations-detected-using-statistical-machine-learning/).

- Corinne Jones, Sophie Clayton, Francois Ribalet, E. Virginia Armbrust, and Zaid Harchaoui. A Kernel-Based Change Detection Method to Map Shifts in Phytoplankton Communities Measured by Flow Cytometry.  *Methods in Ecology and Evolution*, 12, 1687-1698, 2021.  
[[paper]](https://besjournals.onlinelibrary.wiley.com/doi/10.1111/2041-210X.13647) [[code]](https://github.com/cjones6/cytosegmenter)

### Statistical analysis of meteorological models
The effects of a weather model's parameters on the model's forecasts are not well-understood. In this work we performed a sensitivity analysis of the parameters of the COAMPS weather model on the spatial structure of its forecasts. Ideally, we would eventually be able to tune the parameters to improve forecasts.

- Caren Marzban, Corinne Jones, Ning Li, and Scott Sandgathe. On the Effect of Model Parameters on Forecast Objects. *Geoscientific Model Development*, 11, 1577-1590, 2018.  
[[paper]](https://www.geosci-model-dev.net/11/1577/2018/gmd-11-1577-2018.pdf)

### Statistical machine learning for healthcare
Sequences of medial billing codes for millions of patients contain a wealth of information about diseases and people's behaviors. After demonstrating that [canonical correlation analysis](https://en.wikipedia.org/wiki/Canonical_correlation) (CCA) discovers interesting relationships between codes, we explore the effectiveness of using CCA features in predicting elective surgery for diverticulitis. 

- Corinne L. Jones, Sham M. Kakade, Lucas W. Thornblade, David R. Flum, and Abraham D. Flaxman. Canonical correlation analysis for analyzing sequences of medical billing codes. *Proceedings of the 2016 NIPS workshop on Machine Learning for Health*, 2016.

### Machine learning for cyber security
The [STUCCO](https://stucco.github.io/) project at Oak Ridge National Lab aims to synthesize data from a variety of sources to help security analysts quickly learn about potential flaws in their systems.

- Corinne L. Jones, Robert A. Bridges, Kelly M. T. Huffer, and John R. Goodall. Towards a Relation Extraction Framework for Cyber-Security Concepts. *Proceedings of the 10th Annual Cyber and Information Security Research Conference (CISR)*. ACM International Conference Proceedings Series, 2015.
- Robert A. Bridges, Corinne L. Jones, Michael D. Iannacone, Kelly M. Testa, John R. Goodall. Automatic Labeling for Entity Extraction in Cyber Security. *ASE Third International Conference on Cyber Security, Academy of Science and Engineering (ASE),* 2014.

### Statistical analysis of international trade
Economic models of multi-product firms have historically mainly focused on how many goods firms produce, rather than what they produce. Recently we developed a model that accounts for correlations in production efficiencies across products to determine what firms co-export, and we applied the data to Chinese export data.  

I encountered the same Chinese exports dataset when I was an undergraduate. My undergraduate thesis examined the factors that contribute to the extent of [exchange rate pass-through](https://en.wikipedia.org/wiki/Exchange-rate_pass-through) for goods exported by Chinese firms. My advisor was [Kala Krishna](https://sites.google.com/site/kalakrishnapsu/).

- Peter Egger and Corinne Jones. Co-Exportation of Products by Multi-Product Firms. 2023.  
[[paper]](https://virtual.oxfordabstracts.com/#/event/3533/submission/156)  
- Corinne Jones. Exchange rate pass-through: Evidence from China. 2014.

