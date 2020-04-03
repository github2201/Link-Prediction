# Social-Network-Graph-Link-Prediction
#### Problem statement:
Given a directed social graph, have to predict missing links to recommend users (Link Prediction in graph)

- Data columns (total 2 columns):  
- source_node           
- destination_node      

#### Mapping the problem into supervised learning problem:
Generated training samples of good and bad links from given directed graph and for each link got some features like no of followers, is he followed back, page rank,some svd fetures of adj matrix, some weight features etc. and trained ml model based on these features to predict link.

