# Machine Learning Applications For Health Assignment 2

## Author

**Jule Valendo Halim - 1425567**

## Description

This code aims to perform K-Means clustering on records of patients with profound hypotension.

The aims are as follows
- Determining Number of Clusters to Investigate: We use the elbow criteria to evaluate intradistance between the clusters and select optimal clusters to investigate
- Analyzing Patient Outcomes: We investigate whether the chosen number of clusters correlate significantly with patient outcome (mortality rates). The presence of a date of death is used to determine if a patient survived.
- Visualization of Cluster Differences: We aim to create visualizations of the differences between each cluster to illustrate significant differences between them. These visualizations are also used to examine whether they significantly effect patient outcomes.

## Environment Setup
The code is run on python=3.11.9
To run the code, install the required packages using:

pip install -r requirements.txt