# Awesome Outlier Detection Resources [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[![GitHub stars](https://img.shields.io/github/stars/themlphdstudent/awesome-outlier-detection-resources.svg)](https://github.com/themlphdstudent/awesome-outlier-detection-resources/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/themlphdstudent/awesome-outlier-detection-resources.svg?color=blue)](https://github.com/themlphdstudent/awesome-outlier-detection-resources/network)
[![License](https://img.shields.io/github/license/themlphdstudent/awesome-outlier-detection-resources.svg?color=blue)](https://github.com/themlphdstudent/awesome-outlier-detection-resources/blob/master/LICENSE)

</br>

# Outlier Detection
> In data mining, anomaly detection (also outlier detection) is the identification of rare items, events or observations which raise suspicions by differing significantly from the majority of the data. - [Wikipedia](https://en.wikipedia.org/wiki/Anomaly_detection)

</br>

# Table of Contents

- [1. Books](#1.-books)
- [2. Research Papers](#2.-research-papers)
    - [2.1. Survey Papers](##2.1.-survey-papers)
    - [2.2. State-of-the-Art Papers](##2.2.-state-of-the-art-papers)
    - [2.3. Density Based Outlier Detection Methods](##2.3.-density-based-outlier-detection-methods)
    - [2.4. Distance Based Outlier Detection Methods](##2.4.-distance-based-outlier-detection-methods)
    - [2.5. Clustering Based Outlier Detection Methods](##2.5.-clustring-based-outlier-detection-methods)
    - [2.6. Isolation Based Outlier Detection Methods](##2.6.-isolation-based-outlier-detection-methods)
    - [2.7. Subspace Outlier Detection Methods](##2.7.-subspace-outlier-detection-methods)
    - [2.8. Ensemble based Outlier Detection Methods](##2.8.-ensemble-based-outlier-detection-methods)
    - [2.9. Deep Learning Outlier Detection Methods](##2.9.-deep-learning-outlier-detection-methods)
    - [2.10. Outlying Aspect Mining](##2.10.-outlying-aspect-mining)
- [3. Tutorials](#3.-tutorials)
- [4. Datasets](#4.-datasets)

# 1. Books

Outlier Analysis by Charu C. Aggarwal [[URL]](https://www.springer.com/gp/book/9783319475776).

# 2. Research Papers

## 2.1. Survey Papers

| Title | Publication Venue | Year | Reference | URL |
|------|------------|----|--|---|
| Novelty detection: a review—part 1: statistical approaches | Elsevier | 2003 | [[1]](#1) | [[URL]](https://www.sciencedirect.com/science/article/abs/pii/S0165168403002020) |
| Novelty detection: a review—part 2:: neural network based approaches | Elsevier | 2003 | [[2]](#2) | [[URL]](https://www.sciencedirect.com/science/article/abs/pii/S0165168403002032) | 
| A Survey of Outlier Detection Methodologies | Springer | 2004 | [[3]](#3) | [[URL]](https://link.springer.com/article/10.1007/s10462-004-4304-y) [[PDF]](http://eprints.whiterose.ac.uk/767/1/hodgevj4.pdf) |
| Anomaly detection: A survey | ACM | 2009 | [[4]](#4) | [[PDF]](https://dl.acm.org/doi/pdf/10.1145/1541880.1541882)
| A Comprehensive Survey of Data Mining-based Fraud Detection Research | ArXiv Preprint| 2010 | [[15]](#15) | [[PDF]](https://arxiv.org/abs/1009.6119)
| A survey on unsupervised outlier detection in high‐dimensional numerical data | Wiley Online Library | 2012 | [[16]](#16) | [[URL]](https://onlinelibrary.wiley.com/doi/abs/10.1002/sam.11161)
| Survey on Anomaly Detection using Data Mining Techniques | ScienceDirect | 2015 | [[14]](#14) | [[URL]](https://www.sciencedirect.com/science/article/pii/S1877050915023479)
| Graph based anomaly detection and description: a survey | DMKD | 2015 | [[47]](#47) | [[URL]](https://link.springer.com/article/10.1007/s10618-014-0365-y) [[PDF]](https://arxiv.org/pdf/1404.4679.pdf)
| A comparative evaluation of outlier detection algorithms: Experiments and analyses | Pattern Recognition | 2018 | [[48]](#48) | [[PDF]](http://www.eurecom.fr/fr/publication/5334/download/data-publi-5334_2.pdf)
| Progress in outlier detection techniques: A survey | IEEE Access | 2019 | [[46]](#46) | [[URL]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8786096)
| Deep learning for anomaly detection: A survey | ArXiv | 2019 | [[49]](#49) | [[PDF]](https://arxiv.org/pdf/1901.03407.pdf)
| Deep learning for anomaly detection: A review | ArXiv | 2020 | [[50]](#50) | [[PDF]](https://arxiv.org/pdf/2007.02500.pdf)

## 2.2. State-of-the-Art Papers
| Title | Publication Venue | Year | Reference | URL |
|------|------------|----|--|---|
| LOF: Identifying Density-Based Local Outliers | ACM SIGMOD Record | 2000 | [[6]](#6) | [[PDF]](https://www.dbs.ifi.lmu.de/Publikationen/Papers/LOF.pdf)
| Efficient algorithms for mining outliers from large data sets | ACM SIGMOD Record | 2000 | [[17]](#17) | [[PDF]](https://webdocs.cs.ualberta.ca/~zaiane/pub/check/ramaswamy.pdf)
| Fast outlier detection in high dimensional spaces | PKDD | 2002 | [[33]](#33) | [[PDF]](https://link.springer.com/content/pdf/10.1007/3-540-45681-3_2.pdf)
| Isolation Forest | IEEE | 2008 | [[5]](#5) | [[URL]](https://ieeexplore.ieee.org/abstract/document/4781136)

## 2.3. Density Based Outlier Detection Methods

| Title | Publication Venue | Year | Reference | URL |
|------|------------|----|--|---|
| OPTICS-OF: Identifying Local Outliers | Springer | 1999 | [[9]](#9) |[[URL]](https://link.springer.com/chapter/10.1007/978-3-540-48247-5_28)
| LOF: Identifying Density-Based Local Outliers | ACM SIGMOD Record | 2000 | [[6]](#6) | [[PDF]](https://www.dbs.ifi.lmu.de/Publikationen/Papers/LOF.pdf)
| Enhancing effectiveness of outlier detections for low density patterns (COF) | PAKDD | 2002 | [[55]](#55) | [[URL]](https://link.springer.com/chapter/10.1007/3-540-47887-6_53)
| RDF: A density-based outlier detection method using vertical data representation | ICDM | 2004 |[[57]](#57) | [[URL]](https://ieeexplore.ieee.org/abstract/document/1410346)
| LOCI: fast outlier detection using the local correlation integral | IEEE | 2003 | [[7]](#7) |[[URL]](https://ieeexplore.ieee.org/abstract/document/1260802)
| LoOP: local outlier probabilities | CIKM | 2009 |[[58]](#58) | [[PDF]](https://www.dbs.ifi.lmu.de/Publikationen/Papers/LoOP1649.pdf)
| Resolution-based outlier factor: detecting the top-n most outlying data points in engineering data (ROF) | KAIS | 2009 | [[59]](#59) | [[URL]](https://link.springer.com/article/10.1007/s10115-008-0145-3)
| FastLOF: An expectation-maximization based local outlier detection algorithm | ICPR | 2012 | [[60]](#60) | [[URL]](https://ieeexplore.ieee.org/abstract/document/6460620)
| Local outlier detection reconsidered: a generalized view on locality with applications to spatial, video, and network outlier detection (SimplifiedLOF) | DMKD | 2014 | [[56]](#56) | [[URL]](https://link.springer.com/article/10.1007/s10618-012-0300-z)
| LiNearN: A new approach to nearest neighbour density estimator | Pattern Recognition | 2014 | [[52]](#52) | [[URL]](https://www.sciencedirect.com/science/article/pii/S0031320314000314)
| Revisiting Attribute Independence Assumption in Probabilistic Unsupervised Anomaly Detection | Springer | 2016 | [[8]](#8) |[[URL]](https://link.springer.com/chapter/10.1007/978-3-319-31863-9_6)
| Hierarchical density estimates for data clustering, visualization, and outlier detection (GLOSH) | TKDD | 2015 | [[61]](#61) | [[URL]](https://dl.acm.org/doi/abs/10.1145/2733381)
| Improved histogram-based anomaly detector with the extended principal component features | arXiv preprint | 2019 | [[51]](#51) | [[PDF]](https://arxiv.org/pdf/1909.12702)

## 2.4. Distance Based Outlier Detection Methods

| Title | Publication Venue | Year | Reference | URL |
|------|------------|----|--|---|
| Efficient algorithms for mining outliers from large data sets | ACM SIGMOD Record | 2000 | [[17]](#17) | [[PDF]](https://webdocs.cs.ualberta.ca/~zaiane/pub/check/ramaswamy.pdf)
| Fast outlier detection in high dimensional spaces | PKDD | 2002 | [[33]](#33) | [[PDF]](https://link.springer.com/content/pdf/10.1007/3-540-45681-3_2.pdf)
| A New Local Distance-Based Outlier Detection Approach for Scattered Real-World Data | PAKDD | 2009 | [[30]](#30) | [[URL]](https://link.springer.com/chapter/10.1007/978-3-642-01307-2_84)
| Rapid Distance-Based Outlier Detection via Sampling | NIPS | 2013 | [[32]](#32) | [[PDF]](https://papers.nips.cc/paper/5127-rapid-distance-based-outlier-detection-via-sampling.pdf)
| Distance-based Outlier Detection in Data Streams | VLDB | 2016 | [[31]](#31) | [[PDF]](http://www.vldb.org/pvldb/vol9/p1089-tran.pdf)

## 2.5. Clustering Based Outlier Detection Methods

| Title | Publication | Year | Reference | URL |
|------|------------|----|--|---|
| Clustering-Based Outlier Detection Method | FSKD | 2008 | [[35]](#35) | [[URL]](https://ieeexplore.ieee.org/abstract/document/4666153/)
| Efficient Clustering-Based Outlier Detection Algorithm for Dynamic Data Stream | FSKD | 2008 | [[36]](#36) | [[URL]](https://ieeexplore.ieee.org/abstract/document/4666541)
| Cluster-based outlier detection | Annals of Operations Research | 2009 | [[34]](#34) | [[PDF]](https://link.springer.com/content/pdf/10.1007/s10479-008-0371-9.pdf)
| Framework of Clustering-Based Outlier Detection | FSKD  | 2009 | [[40]](#40) | [[URL]](https://ieeexplore.ieee.org/abstract/document/5358544/)
| An Outlier Detection Method Based on Clustering | EAIT | 2011 | [[37]](#37) | [[PDF]](https://www.researchgate.net/profile/Sukumar_Nandi2/publication/232620480_An_Outlier_Detection_Method_Based_on_Clustering/links/02e7e530b17b537e22000000/An-Outlier-Detection-Method-Based-on-Clustering.pdf)
| A Minimum Spanning Tree-Inspired Clustering-Based Outlier Detection Technique | ICDM | 2012 | [[39]](#39) | [[PDF]](https://link.springer.com/content/pdf/10.1007%2F978-3-642-31488-9_17.pdf)
| Cluster Based Outlier Detection Algorithm for Healthcare Data | Procedia Computer Science | 2015 | [[38]](#38) | [[PDF]](https://www.sciencedirect.com/science/article/pii/S1877050915005591/pdf?md5=073c395c49ce2afb477c345be8d92dc6&pid=1-s2.0-S1877050915005591-main.pdf&_valck=1)

## 2.6. Isolation Based Outlier Detection Methods

| Title | Publication Venue | Year | Reference | URL |
|------|------------|----|--|---|
| Isolation Forest | IEEE | 2008 | [[5]](#5) | [[URL]](https://ieeexplore.ieee.org/abstract/document/4781136)
| On Detecting Clustered Anomalies Using SCiForest | Springer | 2010 | [[12]](#12) | [[PDF]](https://link.springer.com/content/pdf/10.1007/978-3-642-15883-4_18.pdf)
| Isolation-Based Anomaly Detection | ACM | 2012 | [[10]](#10) | [[PDF]](https://dl.acm.org/doi/pdf/10.1145/2133360.2133363)
| Improving iForest with Relative Mass | Springer | 2014 | [[11]](#11) |[[URL]](https://link.springer.com/chapter/10.1007/978-3-319-06605-9_42)
| Efficient anomaly detection by isolation using nearest neighbour ensemble | ICDEW | 2014 | [[42]](#42) | [[URL]](https://ieeexplore.ieee.org/abstract/document/7022664)
| LeSiNN: Detecting anomalies by identifying Least Similar Nearest Neighbours | IEEE | 2015 | [[13]](#13) | [[URL]](https://ieeexplore.ieee.org/abstract/document/7395725)
| Isolation‐based anomaly detection using nearest‐neighbor ensembles | Computational Intelligence | 2018 | [[45]](#45) | [[URL]](https://onlinelibrary.wiley.com/doi/abs/10.1111/coin.12156)
| Anomaly Detection Technique Robust to Units and Scales of Measurement | PAKDD | 2018 | [[53]](#53) | [[URL]](https://link.springer.com/chapter/10.1007/978-3-319-93034-3_47)
| usfAD: a robust anomaly detector based on unsupervised stochastic forest | International Journal of Machine Learning and Cybernetics | 2020 | [[54]](#54) | [[URL]](https://link.springer.com/article/10.1007/s13042-020-01225-0)


## 2.7. Subspace Outlier Detection Methods

| Title | Publication Venue | Year | Reference | URL |
|------|------------|----|--|---|
| HiCS: High Contrast Subspaces for Density-Based Outlier Ranking | ACM | 2012 | [[21]](#21) | [[URL]](https://dl.acm.org/doi/10.1109/ICDE.2012.88) |
| Hiding outliers in high-dimensional data spaces| Springer | 2017 | [[22]](#22) | [[URL]](https://link.springer.com/article/10.1007/s41060-017-0068-8) |
| ZERO++: Harnessing the Power of Zero Appearances to Detect Anomalies in Large-Scale Data Sets | JAIR | 2016 | [[23]](#23) | [[URL]](https://jair.org/index.php/jair/article/view/11035) [[PDF]](www.jair.org%2Findex.php%2Fjair%2Farticle%2Fdownload%2F11035%2F26206%2F&usg=AOvVaw01oTULTccwnx2vX6AHq54Y)
| Local Subspace Based Outlier Detection | Springer | 2009 | [[24]](#24) | [[URL]](https://link.springer.com/chapter/10.1007/978-3-642-03547-0_15)
| Subspace Outlier Detection in Linear Time with Randomized Hashing | IEEE | 2016 | [[25]](#25) | [[URL]](https://ieeexplore.ieee.org/document/7837870) [[PDF]](https://saketsathe.net/downloads/rshash.pdf)
| Outlier Detection in Arbitrarily Oriented Subspaces | ICDM | 2012 | [[26]](#26) | [[PDF]](https://www.dbs.ifi.lmu.de/~zimek/publications/ICDM2012/COP.pdf)
| An angle-based subspace anomaly detection approach to high-dimensional data: With an application to industrial fault detection | Elsevier | 2015 | [[27]](#27) | [[URL]](https://www.sciencedirect.com/science/article/abs/pii/S095183201500174X) [[PDF]](https://www.diva-portal.org/smash/get/diva2:986509/FULLTEXT01.pdf)
| Outlier Detection in Axis-Parallel Subspaces of High Dimensional Data | Springer | 2009 | [[28]](#28) | [[URL]](https://link.springer.com/chapter/10.1007/978-3-642-01307-2_86) [[PDF]](https://www.dbs.ifi.lmu.de/Publikationen/Papers/pakdd09_SOD.pdf)

## 2.8. Ensemble based Outlier Detection Methods

| Title | Publication | Year | Reference | URL |
|------|------------|----|--|---|
| LODA | Machine Learning | 2016 | [[62]](#62) | [[PDF]](https://link.springer.com/content/pdf/10.1007/s10994-015-5521-0.pdf)
| LSCP | SIAM | 2019 | [[63]](#63) | [[PDF]](https://arxiv.org/pdf/1812.01528)
| DCSO | ArXiv | 2019 | [[64]](#64) | [[PDF]](https://arxiv.org/pdf/1911.10418)

## 2.9. Deep Learning Outlier Detection Methods

| Title | Publication | Year | Reference | URL |
|------|------------|----|--|---|


## 2.10. Outlying Aspect Mining

| Title | Publication Venue | Year | Reference | URL |
|------|------------|----|--|---|
| Hos-Miner: a system for detecting outlyting subspaces of high-dimensional data | VLDB | 2004 | [[20]](#20) | [[PDF]](https://dl.acm.org/doi/pdf/10.5555/1316689.1316810)
| Mining outlying aspects on numeric data | Springer | 2015 | [[19]](#19) | [[URL]](https://link.springer.com/article/10.1007/s10618-014-0398-2)
| Discovering outlying aspects in large datasets | Springer | 2016 | [[18]](#18) | [[PDF]](https://www.cs.sfu.ca/~jpei/publications/Outlying%20aspects%20DAMI16.pdf)
| Scalable Outlying-Inlying Aspects Discovery via Feature Ranking | PAKDD | 2015 | [[29]](#29) | [[URL]](https://link.springer.com/chapter/10.1007/978-3-319-18032-8_33)
| A new effective and efficient measure for outlying aspect mining | WISE | 2020 | [[41]](#41) | [[URL]](https://link.springer.com/chapter/10.1007/978-3-030-62008-0_32)

# 3. Tutorials
| Title | Publication | Year | Reference | URL |
|------|------------|----|--|---|
| Outlier detection techniques | KDD | 2010 | [[44]](#44) | [[URL]](https://archive.siam.org/meetings/sdm10/tutorial3.pdf?source=post_page---------------------------)
| Which Outlier Detector Should I use? | ICDE | 2018 | [[43]](#43) | [[URL]](https://ieeexplore.ieee.org/abstract/document/8594824)

# 4. Datasets

[ODDS - Outlier Detection DataSets](http://odds.cs.stonybrook.edu)

# References

|  |  |
|---|---|
| <a id='1'> [1] </a> | Markou, M., & Singh, S. (2003). Novelty detection: a review—part 1: statistical approaches. Signal processing, 83(12), 2481-2497.
| <a id='2'> [2] </a> | Markou, M., & Singh, S. (2003). Novelty detection: a review—part 2:: neural network based approaches. Signal processing, 83(12), 2499-2521.
| <a id='3'> [3] </a> | Hodge, V., & Austin, J. (2004). A survey of outlier detection methodologies. Artificial intelligence review, 22(2), 85-126.
| <a id='4'> [4] </a> | Chandola, V., Banerjee, A., & Kumar, V. (2009). Anomaly detection: A survey. ACM computing surveys (CSUR), 41(3), 1-58.
| <a id='5'> [5] </a> | Liu, F. T., Ting, K. M., & Zhou, Z. H. (2008, December). Isolation forest. In 2008 Eighth IEEE International Conference on Data Mining (pp. 413-422). IEEE.
| <a id='6'> [6] </a> | Breunig, M. M., Kriegel, H. P., Ng, R. T., & Sander, J. (2000, May). LOF: identifying density-based local outliers. In Proceedings of the 2000 ACM SIGMOD international conference on Management of data (pp. 93-104).
| <a id='7'> [7] </a> | Papadimitriou, S., Kitagawa, H., Gibbons, P. B., & Faloutsos, C. (2003, March). Loci: Fast outlier detection using the local correlation integral. In Proceedings 19th international conference on data engineering (Cat. No. 03CH37405) (pp. 315-326). IEEE.
| <a id='8'> [8] </a> | Aryal, S., Ting, K. M., & Haffari, G. (2016, April). Revisiting attribute independence assumption in probabilistic unsupervised anomaly detection. In Pacific-Asia Workshop on Intelligence and Security Informatics (pp. 73-86). Springer, Cham.
| <a id='9'> [9] </a> | Breunig, M. M., Kriegel, H. P., Ng, R. T., & Sander, J. (1999, September). Optics-of: Identifying local outliers. In European Conference on Principles of Data Mining and Knowledge Discovery (pp. 262-270). Springer, Berlin, Heidelberg.
| <a id='10'> [10] </a> | Liu, F. T., Ting, K. M., & Zhou, Z. H. (2012). Isolation-based anomaly detection. ACM Transactions on Knowledge Discovery from Data (TKDD), 6(1), 1-39.
| <a id='11'> [11] </a> | Aryal, S., Ting, K. M., Wells, J. R., & Washio, T. (2014, May). Improving iforest with relative mass. In Pacific-Asia Conference on Knowledge Discovery and Data Mining (pp. 510-521). Springer, Cham.
| <a id='12'> [12] </a> | Liu, F. T., Ting, K. M., & Zhou, Z. H. (2010, September). On detecting clustered anomalies using SCiForest. In Joint European Conference on Machine Learning and Knowledge Discovery in Databases (pp. 274-290). Springer, Berlin, Heidelberg.
| <a id='13'> [13] </a> | Pang, G., Ting, K. M., & Albrecht, D. (2015, November). LeSiNN: Detecting anomalies by identifying least similar nearest neighbours. In 2015 IEEE international conference on data mining workshop (ICDMW) (pp. 623-630). IEEE.
| <a id='14'> [14] </a> | Agrawal, S., & Agrawal, J. (2015). Survey on anomaly detection using data mining techniques. Procedia Computer Science, 60, 708-713.
| <a id='15'> [15] </a> | Phua, C., Lee, V., Smith, K., & Gayler, R. (2010). A comprehensive survey of data mining-based fraud detection research. arXiv preprint arXiv:1009.6119.
| <a id='16'> [16] </a> | Zimek, A., Schubert, E., & Kriegel, H. P. (2012). A survey on unsupervised outlier detection in high‐dimensional numerical data. Statistical Analysis and Data Mining: The ASA Data Science Journal, 5(5), 363-387.
| <a id='17'> [17] </a> | Ramaswamy, S., Rastogi, R., & Shim, K. (2000, May). Efficient algorithms for mining outliers from large data sets. In Proceedings of the 2000 ACM SIGMOD international conference on Management of data (pp. 427-438).
| <a id='18'> [18] </a> | Vinh, N. X., Chan, J., Romano, S., Bailey, J., Leckie, C., Ramamohanarao, K., & Pei, J. (2016). Discovering outlying aspects in large datasets. Data mining and knowledge discovery, 30(6), 1520-1555.
| <a id='19'> [19] </a> | Duan, L., Tang, G., Pei, J., Bailey, J., Campbell, A., & Tang, C. (2015). Mining outlying aspects on numeric data. Data Mining and Knowledge Discovery, 29(5), 1116-1151.
| <a id='20'> [20] </a> | Zhang, J., Lou, M., Ling, T. W., & Wang, H. (2004). HOS-miner: A system for detecting outlying subspaces of high-dimensional data. In Proceedings of the 30th International Conference on Very Large Data Bases (VLDB'04) (pp. 1265-1268). Morgan Kaufmann Publishers Inc..
| <a id='21'> [21] </a> | Keller, F., Muller, E., & Bohm, K. (2012, April). HiCS: High contrast subspaces for density-based outlier ranking. In 2012 IEEE 28th international conference on data engineering (pp. 1037-1048). IEEE.
| <a id='22'> [22] </a> | Steinbuss, G., & Böhm, K. (2017). Hiding outliers in high-dimensional data spaces. International Journal of Data Science and Analytics, 4(3), 173-189.
| <a id='23'> [23] </a> | Pang, G., Ting, K. M., Albrecht, D., & Jin, H. (2016). ZERO++: Harnessing the power of zero appearances to detect anomalies in large-scale data sets. Journal of Artificial Intelligence Research, 57, 593-620.
| <a id='24'> [24] </a> | Agrawal, A. (2009, August). Local subspace based outlier detection. In International Conference on Contemporary Computing (pp. 149-157). Springer, Berlin, Heidelberg.
| <a id='25'> [25] </a> | Sathe, S., & Aggarwal, C. C. (2016, December). Subspace outlier detection in linear time with randomized hashing. In 2016 IEEE 16th International Conference on Data Mining (ICDM) (pp. 459-468). IEEE.
| <a id='26'> [26] </a> | Kriegel, H. P., Kröger, P., Schubert, E., & Zimek, A. (2012, December). Outlier detection in arbitrarily oriented subspaces. In 2012 IEEE 12th international conference on data mining (pp. 379-388). IEEE.
| <a id='27'> [27] </a> | Zhang, L., Lin, J., & Karim, R. (2015). An angle-based subspace anomaly detection approach to high-dimensional data: With an application to industrial fault detection. Reliability Engineering & System Safety, 142, 482-497.
| <a id='28'> [28] </a> | Kriegel, H. P., Kröger, P., Schubert, E., & Zimek, A. (2009, April). Outlier detection in axis-parallel subspaces of high dimensional data. In Pacific-Asia Conference on Knowledge Discovery and Data Mining (pp. 831-838). Springer, Berlin, Heidelberg.
| <a id='29'> [29] </a> | Vinh, N. X., Chan, J., Bailey, J., Leckie, C., Ramamohanarao, K., & Pei, J. (2015, May). Scalable outlying-inlying aspects discovery via feature ranking. In Pacific-Asia Conference on Knowledge Discovery and Data Mining (pp. 422-434). Springer, Cham.
| <a id='30'> [30] </a> | Zhang, K., Hutter, M., & Jin, H. (2009, April). A new local distance-based outlier detection approach for scattered real-world data. In Pacific-Asia Conference on Knowledge Discovery and Data Mining (pp. 813-822). Springer, Berlin, Heidelberg.
| <a id='31'> [31] </a> | Tran, L., Fan, L., & Shahabi, C. (2016). Distance-based outlier detection in data streams. Proceedings of the VLDB Endowment, 9(12), 1089-1100.
| <a id='32'> [32] </a> | Sugiyama, M., & Borgwardt, K. (2013). Rapid distance-based outlier detection via sampling. In Advances in Neural Information Processing Systems (pp. 467-475).
| <a id='33'> [33] </a> | Angiulli, F., & Pizzuti, C. (2002, August). Fast outlier detection in high dimensional spaces. In European conference on principles of data mining and knowledge discovery (pp. 15-27). Springer, Berlin, Heidelberg.
| <a id='34'> [34] </a> | Duan, L., Xu, L., Liu, Y., & Lee, J. (2009). Cluster-based outlier detection. Annals of Operations Research, 168(1), 151-168.
| <a id='35'> [35] </a> | Jiang, S. Y., & An, Q. B. (2008, October). Clustering-based outlier detection method. In 2008 Fifth International Conference on Fuzzy Systems and Knowledge Discovery (Vol. 2, pp. 429-433). IEEE.
| <a id='36'> [36] </a> | Elahi, M., Li, K., Nisar, W., Lv, X., & Wang, H. (2008, October). Efficient clustering-based outlier detection algorithm for dynamic data stream. In 2008 Fifth International Conference on Fuzzy Systems and Knowledge Discovery (Vol. 5, pp. 298-304). IEEE.
| <a id='37'> [37] </a> | Pamula, R., Deka, J. K., & Nandi, S. (2011, February). An outlier detection method based on clustering. In 2011 Second International Conference on Emerging Applications of Information Technology (pp. 253-256). IEEE.
| <a id='38'> [38] </a> | Christy, A., Gandhi, G. M., & Vaithyasubramanian, S. (2015). Cluster based outlier detection algorithm for healthcare data. Procedia Computer Science, 50, 209-215.
| <a id='39'> [39] </a> | Wang, X., Wang, X. L., & Wilkes, D. M. (2012, July). A minimum spanning tree-inspired clustering-based outlier detection technique. In Industrial Conference on Data Mining (pp. 209-223). Springer, Berlin, Heidelberg.
| <a id='40'> [40] </a> | Jiang, S. Y., & Yang, A. M. (2009, August). Framework of clustering-based outlier detection. In 2009 Sixth International Conference on Fuzzy Systems and Knowledge Discovery (Vol. 1, pp. 475-479). IEEE.
| <a id='41'> [41] </a> | Samariya, D., Aryal, S., Ting, K. M., & Ma, J. (2020, October). A new effective and efficient measure for outlying aspect mining. In International Conference on Web Information Systems Engineering (pp. 463-474). Springer, Cham.
| <a id='42'> [42] </a> | T. R. Bandaragoda, K. M. Ting, D. Albrecht, F. T. Liu and J. R. Wells, "Efficient Anomaly Detection by Isolation Using Nearest Neighbour Ensemble," 2014 IEEE International Conference on Data Mining Workshop, Shenzhen, 2014, pp. 698-705, doi: 10.1109/ICDMW.2014.70.
| <a id='43'> [43] </a> | Ting, K. M., Aryal, S., & Washio, T. (2018, November). Which Outlier Detector Should I use?. In 2018 IEEE International Conference on Data Mining (ICDM) (pp. 8-8). IEEE.
| <a id='44'> [44] </a> | Kriegel, H. P., Kröger, P., & Zimek, A. (2010). Outlier detection techniques. Tutorial at KDD, 10, 1-76.
| <a id='45'> [45] </a> | Bandaragoda, T. R., Ting, K. M., Albrecht, D., Liu, F. T., Zhu, Y., & Wells, J. R. (2018). Isolation‐based anomaly detection using nearest‐neighbor ensembles. Computational Intelligence, 34(4), 968-998.
| <a id='46'> [46] </a> | Wang, H., Bah, M. J., & Hammad, M. (2019). Progress in outlier detection techniques: A survey. IEEE Access, 7, 107964-108000.
| <a id='47'> [47] </a> | Akoglu, L., Tong, H., & Koutra, D. (2015). Graph based anomaly detection and description: a survey. Data mining and knowledge discovery, 29(3), 626-688.
| <a id='48'> [48] </a> | Domingues, R., Filippone, M., Michiardi, P., & Zouaoui, J. (2018). A comparative evaluation of outlier detection algorithms: Experiments and analyses. Pattern Recognition, 74, 406-421.
| <a id='49'> [49] </a> | Chalapathy, R., & Chawla, S. (2019). Deep learning for anomaly detection: A survey. arXiv preprint arXiv:1901.03407.	
| <a id='50'> [50] </a> | Pang, G., Shen, C., Cao, L., & Hengel, A. V. D. (2020). Deep learning for anomaly detection: A review. arXiv preprint arXiv:2007.02500.
| <a id='51'> [51] </a> | Aryal, S., Baniya, A. A., & Santosh, K. C. (2019). Improved histogram-based anomaly detector with the extended principal component features. arXiv preprint arXiv:1909.12702.
| <a id='52'> [52] </a> | Wells, J. R., Ting, K. M., & Washio, T. (2014). LiNearN: A new approach to nearest neighbour density estimator. Pattern Recognition, 47(8), 2702-2720.
| <a id='53'> [53] </a> | Aryal, S. (2018, June). Anomaly detection technique robust to units and scales of measurement. In Pacific-Asia Conference on Knowledge Discovery and Data Mining (pp. 589-601). Springer, Cham.
| <a id='54'> [54] </a> | Aryal, S., Santosh, K. C., & Dazeley, R. (2020). usfAD: a robust anomaly detector based on unsupervised stochastic forest. International Journal of Machine Learning and Cybernetics, 1-14.
| <a id='55'> [55] </a> | Tang, J., Chen, Z., Fu, A. W. C., & Cheung, D. W. (2002, May). Enhancing effectiveness of outlier detections for low density patterns. In Pacific-Asia Conference on Knowledge Discovery and Data Mining (pp. 535-548). Springer, Berlin, Heidelberg.
| <a id='56'> [56] </a> | Schubert, E., Zimek, A., & Kriegel, H. P. (2014). Local outlier detection reconsidered: a generalized view on locality with applications to spatial, video, and network outlier detection. Data mining and knowledge discovery, 28(1), 190-237.
| <a id='57'> [57] </a> | Ren, D., Wang, B., & Perrizo, W. (2004, November). Rdf: A density-based outlier detection method using vertical data representation. In Fourth IEEE International Conference on Data Mining (ICDM'04) (pp. 503-506). IEEE.
| <a id='58'> [58] </a> | Kriegel, H. P., Kröger, P., Schubert, E., & Zimek, A. (2009, November). LoOP: local outlier probabilities. In Proceedings of the 18th ACM conference on Information and knowledge management (pp. 1649-1652).
| <a id='59'> [59] </a> | Fan, H., Zaïane, O. R., Foss, A., & Wu, J. (2009). Resolution-based outlier factor: detecting the top-n most outlying data points in engineering data. Knowledge and Information Systems, 19(1), 31-51.
| <a id='60'> [60] </a> | Goldstein, M. (2012, November). FastLOF: An expectation-maximization based local outlier detection algorithm. In Proceedings of the 21st International Conference on Pattern Recognition (ICPR2012) (pp. 2282-2285). IEEE.
| <a id='61'> [61] </a> | Campello, R. J., Moulavi, D., Zimek, A., & Sander, J. (2015). Hierarchical density estimates for data clustering, visualization, and outlier detection. ACM Transactions on Knowledge Discovery from Data (TKDD), 10(1), 1-51.
| <a id='62'> [62] </a> | Pevný, T. (2016). Loda: Lightweight on-line detector of anomalies. Machine Learning, 102(2), 275-304.
| <a id='63'> [63] </a> | Zhao, Y., Nasrullah, Z., Hryniewicki, M. K., & Li, Z. (2019, May). LSCP: Locally selective combination in parallel outlier ensembles. In Proceedings of the 2019 SIAM International Conference on Data Mining (pp. 585-593). Society for Industrial and Applied Mathematics.
| <a id='64'> [64] </a> | Zhao, Y., & Hryniewicki, M. K. (2019). DCSO: dynamic combination of detector scores for outlier ensembles. arXiv preprint arXiv:1911.10418.
| <a id='65'> [65] </a> |
| <a id='66'> [66] </a> |
| <a id='67'> [67] </a> |


----
**More to come...**

More items will be added to the repository. Please feel free to suggest other key resources by opening an issue report, submitting a pull request, or dropping me an email @ (samariya.durgesh@gmail.com). Enjoy reading!

Last updated on November 25, 2020
