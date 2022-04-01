# bachelors_dissertation
Bachelors dissertation seeking to understand human mobility behaviour using unsupervised approaches on WiFi traceset data.

Executive Summary - 

From a basic review of human mobility, it is clear that there is a lack of research linking the classification of individuals/groups within a system; this paper seeks to achieve this. Being able to understand group behaviours, create links between unlabelled data and group behaviours is a significant technique. In this case using a university campus dataset, provides an approach that could be utilised to aid the design of commercial spaces to maximise utilisation of spaces, design evacuation routes, and target group behaviours and movement patterns of classified groups of people.

Using an unlabelled dataset based on data from the connection logs for all the WiFi access points on the KTH University Campus in Sweden the study used a number of clustering algorithms to classify and analyse the data, including a technique to add value to WiFi connection logs in order to aid the classification.

The research tested a range of unsupervised clustering schemes and utilised data processing techniques to aid the classification and analysis of the dataset, including adapting the dataset to summarise user movements through the system1. The implementation used three common machine learning pre-processing techniques: correlation matrix; PCA dimension reduction; and, MinMax normalisation. To evaluate the results using this method, the approach allowed for individuals to be characterised into groups against a number of differentiating criteria in effect creating group ground truths.

The analysis of this research proved that from the tested techniques, Gaussian mixture clustering provided the most consistent scheme for classification of the unlabelled dataset. The correlation matrix approach was ineffective when working with the limited number of parameters within the processed dataset. However, using normalisation and PCA dimension reduction increased the accuracy of model classification. This approach, utilising the feature creation scheme, pre-processing techniques and gaussian mixture clustering has potential to be utilised with other human mobility systems such as shopping centres, transport hubs and government buildings.

The challenge of this type of research is the limitation of unlabelled datasets and WiFi access logs, being able to implement summarising features significantly boosted the interpretability of the data and consequently made classification not only possible but accurate. This paper also reflects on issues related to social and ethical implications of using data which is characterised as sensitive and protected.

The research has been bounded and in part limited by the datasets, the focus is on the approach to the analysis utilising readily available data, the research has however demonstrated/proved an analysis framework that could be applied to datasets of varying scenarios using the same data acquisition techniques.
