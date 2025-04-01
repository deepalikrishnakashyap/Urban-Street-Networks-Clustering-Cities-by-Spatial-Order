# Urban-Street-Networks-Clustering-Cities-by-Spatial-Order
This project explores clustering techniques to analyze urban street network patterns using data from 100 global cities. By applying K-Means and Hierarchical Clustering, we uncover similarities in street orientation, configuration, and entropy, providing insights into urban spatial structures.

# Objective

This project provides hands-on experience in implementing clustering techniques on real-world urban street network datasets. By analyzing street orientation, configuration, and entropy metrics, we aim to explore clustering methods such as K-Means and Hierarchical Clustering to uncover patterns in urban spatial order across global cities.
Background

The study "Urban Spatial Order: Street Network Orientation, Configuration, and Entropy" by Geoff Boeing examines street network patterns in 100 cities worldwide using OpenStreetMap data and the OSMnx software. The research introduces entropy of street bearings and other key metrics such as:

Average street segment length

Circuity (deviation from straight-line distance)

Node degree (number of connections at intersections)

Proportions of intersections vs. dead-ends

Orientation-order (a measure of grid-like structure)

By leveraging these metrics, the study identifies regional clustering patterns, particularly differences between U.S./Canadian cities and those in other parts of the world. This project will reproduce and extend aspects of this analysis using clustering techniques to categorize cities based on their street network characteristics.

# Dataset

We will utilize Table 1 from the research paper, which contains street network measurements for 100 cities. The dataset is available at:
🔗 Urban Spatial Order: Street Network Orientation, Configuration, and Entropy

https://appliednetsci.springeropen.com/articles/10.1007/s41109-019-0189-1 

# Tasks
1. Understanding the Methodology

    Read the research paper to understand the statistical techniques and metrics used.

    Identify key variables and how they contribute to urban spatial order.

2. Data Preprocessing

    Load and explore Table 1 from the dataset.

    Check for missing values, outliers, and inconsistencies.

    Normalize or scale features if necessary.

    Investigate why maintaining a uniform scale is important for clustering methods like K-Means and Hierarchical Clustering.

    Determine whether scaling techniques are required for this dataset.

3. Implementing Clustering Techniques
K-Means Clustering

    Apply K-Means clustering to categorize cities based on street network features.

    Use the Elbow Method to determine the optimal number of clusters.

    Visualize clustering results using appropriate plots.

Hierarchical Clustering

  Implement Hierarchical Clustering with different linkage criteria (single, complete, average, ward).

  Plot dendrograms for each linkage method.

  Compare clustering solutions and interpret differences.

4. Analyzing Clustering Results

    Generate final clustering solutions based on similarity patterns among cities.

    Identify key characteristics of each cluster.

    Investigate whether cities within the same cluster share similar urban design and planning attributes.

    Provide insights into how clustering enhances our understanding of urban spatial structures.
