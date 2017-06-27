
## Abstract

The data sets released here has been used in our study on quantitatively evaluating the impact of disasters in the city. The study of disaster events and their impact in the urban space has been traditionally conducted through manual collections and analysis of surveys, questionnaires and authority documents. While there have been increasingly rich troves of human behavioral data related to the events of interest, the ability to obtain hindsight following a disaster event has not been scaled up. In this study, we propose a novel approach for analyzing events called PairFac. PairFac utilizes discriminant tensor analysis to automatically discover the impact of a major event from rich human behavioral data. Our method aims to (i) uncover the persistent patterns across multiple interrelated aspects of urban behavior (e.g., when, where and what citizens do in a city) and at the same time (ii) identify the salient changes following a potentially impactful event. We show the effectiveness of PairFac in comparison with previous methods through extensive experiments. We also demonstrate the advantages of our approach through case studies with real-world traffic sensor data and social media streams surrounding the 2015 terrorist attacks in Paris. Our work has both methodological contributions in studying the impact of an external stimulus on a system as well as practical implications in the area of disaster event analysis and assessment.

## Data

There are two datasets used in this study, traffic sensor dataset and social media dataset.   

Traffic Sensor dataset was collected from open data Paris. This dataset includes all the hourly data for the flow and the occupancy rate assembled by the permanent traffic sensors installed on the Paris City network (urban network and peripheral boulevard). For interested readers, please direct to the link as: https://opendata.paris.fr/explore/dataset/comptages-routiers-permanents/

Social media dataset was collected from Twitter API. The dataset contains geo-tagged tweets from Paris collected through Twitter API between the period of Oct 16th, 2015 and Nov 20, 2015. 75,982 geo-located tweets were extracted during the period covered.

Duration: 2015-10-16 to 2015-11-20.

Total number of tweets: 75,982

## Publication

If you make use of this data set, please kindly cite:

Xidao Wen, Yu-Ru Lin, and Konstantinos Pelechrinis. 2016. PairFac: Event Analytics through Discriminant Tensor Factorization. In Proceedings of the 25th ACM International on Conference on Information and Knowledge Management (CIKM '16). ACM, New York, NY, USA, 519-528. DOI: https://doi.org/10.1145/2983323.2983837
