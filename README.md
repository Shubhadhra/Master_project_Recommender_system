# Master_project_Recommender_system - Semantic Web based recommender system using Knowledge graphs as source for data. 

Abstract of the the project work:
=================================
Tourism Recommender Systems (TRS) are used to recommend visit plans for tourists. In this project, we design a recommender system to recommend a one day visit plan to the users based on their preferences. For this purpose, we collect tourism domain related data from various data sources available in the web. However, the connectivity between web pages are in the form of hyperlinks and the data at lower level are not connected. Because of this, combining the data obtained from various sources becomes challenging. Semantic web helps us to overcome this problem. It represents data at lower level and they are well connected, thus making it possible to combine data from different sources. So we make use of it in this project to integrate data from various publicly available knowledge graphs. We find suitable datasets in the Linked Open Data and try to obtain relevant tourism domain based information, like the Point of Interests of a city. This is done by querying the SPARQL end points of the respective datasets chosen. Further we can apply federation to combine information from different datasets. Finally, we make use of the federated data to design a recommender system which constructs a personalized visit plan for the user.

Files and details:
==================
=> Data dumps are included with extension '.n3'. SPARQL is used to fetch data triples from knowledge graphs. Respective queries can be found in  'QueriesToRetrieveSubGraphs.py'.

=> The Recommender code is developed using Python and can be found in 'Recommender.py'.

=> Program acceptable format of user input is also included in the text file 'userinput'. Based on user given details the recommender system computes and suggests an optimal day trip plan for the user.
