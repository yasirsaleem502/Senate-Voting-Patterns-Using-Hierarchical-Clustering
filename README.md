# Senate-Voting-Patterns-Using-Hierarchical-Clustering

![Python](https://img.shields.io/badge/Python-3.8+-green)
![Jupyter Notebook](https://img.shields.io/badge/Tools-Jupyter%20Notebook-orange)
![Scikit-learn](https://img.shields.io/badge/Library-Scikit--learn-blue)
![Pandas](https://img.shields.io/badge/Library-Pandas-yellow)
![Matplotlib](https://img.shields.io/badge/Library-Matplotlib-lightblue)

## Project Overview
The Senate Voting Patterns Using Hierarchical Clustering project aims to uncover patterns in the voting behavior of senators by employing a powerful machine learning technique known as Hierarchical Clustering. By clustering senators based on their voting records, the project reveals groupings and voting alliances within the Senate, which may not be evident through traditional analysis. These insights help in understanding political polarization, party loyalty, and the formation of coalitions across party lines. 

## Objective
The primary objective of this project is to apply Hierarchical Clustering  to identify natural groupings of senators based on their voting similarities. This clustering will:

- Provide insights into voting blocks.
- Reveal trends in bipartisan behaviour.
- Identify senators who frequently cross party lines

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Results](#results)
- [Contact](#contact)
  
## Introduction
The Senate is often polarized along party lines, but there are instances where bipartisan cooperation occurs. By applying Hierarchical Clustering, this project aims to group senators based on the similarity of their voting records, revealing key insights into voting blocks, outliers, and coalition building.

## Features

- Hierarchical Clustering: Uses agglomerative clustering to create a hierarchy of voting similarities among senators.
- Visualization: Dendrogram plots visualize the clustering process and highlight voting groups.
- Voting Insights: Identifies patterns of party loyalty, bipartisan coalitions, and outlier behavior in the Senate.

## Dataset
The dataset includes:

- name:  This column contains the names of the senators. Each row represents an individual senator.

- party:  The political party affiliation of the senators. R stands for Republican, and D stands for Democrat.

- state: The U.S. state that the senator represents. This is provided as a two-letter abbreviation (e.g., TN for Tennessee, NH for New Hampshire).

- Bill_1, Bill_2, Bill_3, …, Bill_9:     These columns represent different bills that the senators voted on. Each bill is numbered accordingly (e.g., Bill_1, Bill_4, Bill_5, etc.).

dataset link: https://www.kaggle.com/datasets/muhammadyasirsaleem/u-s-senate-voting-dataset


## Methodology

1 Data Preprocessing: 

Voting records are cleaned and transformed into a numerical format.

2 Clustering Algorithm:

Hierarchical Clustering is applied using the Euclidean distance metric. The clustering algorithm groups senators based on voting similarity.

3 Visualization: 

A Dendrogram is generated to visualize the hierarchical structure of clusters.

## Results
The clustering results reveal clear divisions along party lines but also highlight bipartisan clusters and outliers.
A dendrogram visualizes how senators are grouped based on their voting patterns.



## dendrogram
![sentor dendogram](https://github.com/user-attachments/assets/7f0417cc-f5e0-4854-8e79-18642eb657e0)

## adjusted_rand_score
![sentaor dendgram](https://github.com/user-attachments/assets/ae09dea4-f469-4273-b7f7-1e2ea8e3a987)


 ## Visualization with Seaborn's cluster map
 ![clustermap](https://github.com/user-attachments/assets/5c439a82-3590-43f9-bfc2-90a383b706f6)


 ## Contact

- Author: Muhammad Yasir Saleem
- Email: myasirsaleem94@gmail.com
- LinkedIn:https://www.linkedin.com/in/muhammad-yasir-saleem/


Feel free to reach out if you have any questions or need further information.





