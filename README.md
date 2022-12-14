# dga_anomaly
Four anomaly detection methods are explored with bagging and stacking ensembling to see if performing anomaly detection helps improve the classification of domains, especially adversarially generated domains. This uses data containing benign and AGD domains obtained from the DMD2018 dataset [1], and adversarial domain data obtained from https://github.com/liorsidi/Adversarial-DGA-Datasets [2][3].

[1] Vinayakumar R, Soman KP, Prabaharan Poornachandran, Mamoun Alazab, and Sabu M. Thampi, [AmritaDGA: A Comprehensive Data set for Domain Generation Algorithms (DGAs)] (https://www.researchgate.net/publication/334570954_AmritaDGA_a_comprehensive_data_set_for_domain_generation_algorithms_DGAs_based_domain_name_detection_systems_and_application_of_deep_learning) In Big Data Recommender Systems: Recent Trends and Advances, Institution of Engineering and Technology (IET)

[2] Lior Sidi, Asaf Nadler, and Asaf Shabtai. "MaskDGA: A black-box evasion technique against DGA classifiers and adversarial defenses."(2019).

[3] Lior Sidi, Yisroel Mirsky, Asaf Nadler, Yuval Elovici and Asaf Shabtai. "Helix: DGA Domain Embeddings for Tracking and Exploring Botnets" (2020).