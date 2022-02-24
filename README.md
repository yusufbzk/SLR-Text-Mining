# SLR-Text-Mining

This repository provides the data and the RapidMiner process as well as the Gephi project to re-implement the example described in the paper. 
We collected the data set for the example from four scientific databases: IEEE, EBSCO, ACM, and Web of Science. Only peer-reviewed articles with the terms "smart city" OR "smart cities" in the title and published in the 2009–2019 period were included in the search. Of the articles, 2264 came from IEEE, 453 from EBSCO, 325 from ACM, and 1828  from Web of Science. For the integration and management of the individual data exports, we used the reference management software Citavi 6. After removing duplicates, we exported the entire library with 4219 articles in total as an Excel file. The exported data set was processed with RapidMiner according to the ML-SLR framework and visualized with Gephi. RapidMiner is a machine learning and data mining environment that is a suitable tool for the ML-SLR framework because of its text processing extensions. For the visualization of interactive and complex graphs, we used the open source software Gephi, with a focus on network analysis.

Steps:
1) Install RapidMiner and follow readme in folder RapidMiner
2) Install Gephi and follow readme in Gephi folder 
