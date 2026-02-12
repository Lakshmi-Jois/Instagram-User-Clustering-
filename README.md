# Multi-Level Instagram User Engagement Segmentation Using Unsupervised Machine Learning

## Project Overview

This project focuses on identifying behavioral engagement patterns among
Instagram users using unsupervised machine learning techniques. The goal
was to perform both macro-level segmentation and deep behavioral
profiling to generate actionable user personas for product, marketing,
and business strategy applications.

The analysis was performed on a high-dimensional behavioral dataset
containing \~15K+ user records and 50+ demographic, lifestyle, and
platform interaction features.

------------------------------------------------------------------------

## Objectives

-   Identify primary user engagement segments
-   Discover deeper behavioral subsegments within engagement groups
-   Validate cluster stability using statistical methods
-   Translate machine learning output into business-friendly user
    personas
-   Perform cross-segmentation using demographic and geographic
    variables

------------------------------------------------------------------------

## Dataset Description

Rows: \~15,000+\
Columns: 50+ Features

Feature Categories: - Demographics (Age, Gender, Country, Employment
Status) - Lifestyle Metrics (Exercise, Sleep, Stress, Health
Indicators) - Instagram Behavior Metrics (Sessions, Posts, Reels, Likes,
Comments, DMs, Time Spent)

------------------------------------------------------------------------

## Methodology

### Data Preprocessing

-   Numeric feature extraction
-   Missing value handling
-   Feature scaling using StandardScaler

### Primary Segmentation (K-Means)

-   Subsampling used for scalability
-   Optimal K selection using:
    -   Elbow Method
    -   Silhouette Score
    -   Stability-based Cross-Validation

### Deep Behavioral Profiling (Hierarchical Clustering)

-   Agglomerative Hierarchical Clustering applied within primary
    clusters
-   Dendrogram analysis used to determine subcluster structure
-   Subcluster label propagation to full dataset using Random Forest
    classifier

### Validation Techniques Used

-   Subsample Distribution Validation (KS Test)
-   Silhouette Score Analysis
-   Stability Testing via Multiple Sampling Runs

------------------------------------------------------------------------

## Key Findings

-   Two primary engagement segments identified:
    -   Medium Engagement Users
    -   High Engagement Users
-   High Engagement Users further split into two behavioral types:
    -   Passive High Consumption Users
    -   Active Social / Creator-Type Users
-   Behavioral patterns were largely consistent across employment groups
-   High engagement user concentration highest in:
    -   United States
    -   India
    -   Brazil

------------------------------------------------------------------------

## Business Impact

Marketing: - Target high engagement social users for premium features -
Improve engagement campaigns for passive users

Product: - Personalize feature exposure based on behavior type - Improve
content recommendation strategies

Monetization: - Identify high-value engagement segments - Optimize ad
targeting strategies

------------------------------------------------------------------------

## Tech Stack

-   Python
-   Pandas / NumPy
-   Scikit-Learn
-   SciPy
-   Matplotlib / Plotly

------------------------------------------------------------------------

## Advanced Concepts Applied

-   Multi-Level Clustering Strategy
-   Cluster Stability Validation
-   Subsample-Based Large Data Handling
-   Hierarchical Deep-Dive Segmentation
-   ML-to-Business Translation

------------------------------------------------------------------------

## Author

Lakshmi BS
Data Science \| Machine Learning \| User Behavior Analytics
