# K-Means Clustering Assignment

This repository contains my implementation of the K-Means Clustering and Bisecting K-Means Clustering algorithms for the Industrial Engineering assignment at METU. The dataset and tasks are divided into two parts as described below.

## Part I: Dermatology Dataset

### Objective
Cluster patients into groups using K-Means and Bisecting K-Means algorithms.

### Dataset
- **Name**: Dermatology.xls
- **Description**: Contains information on 366 patients with 33 categorical measurements (assumed as continuous for this task).

### Tasks
#### 1. K-Means Clustering (k=10)
- Run the algorithm with 500 initializations.
- Report:
  - Distance measure used and its justification.
  - Data preprocessing steps (e.g., normalization).
  - Best SSE value and cluster sizes.
  - Total computation time.

#### 2. Bisecting K-Means (k=10)
- Run with 50 and 100 initializations in each iteration.
- Report:
  - SSE value and cluster sizes.
  - Total computation time.
  - Comparison with K-Means results.

#### 3. Comparison Across Clusters (k=3 to k=10)
- Run both algorithms for different cluster counts.
- Report and compare:
  - SSE values.
  - Computing times.
- Determine the best `k` value based on SSE.

---

## Part II: University Rankings Dataset

### Objective
Cluster universities and impute missing values using the clustering approach.

### Dataset
- **Name**: Universities.xls
- **Description**: Contains 1302 records of American colleges and universities with 20 measurements.

### Tasks
#### 1. Preprocessing
- Remove records with missing values.

#### 2. K-Means Clustering
- Cluster continuous measurements.
- Determine the best `k` value using SSE.
- Plot SSE vs. `k`.

#### 3. Cluster Analysis
- Summarize statistics for each cluster (mean, max, min, etc.).
- Describe clusters in the context of their characteristics.

#### 4. Categorical Data Analysis
- Use categorical variables (e.g., State, Private/Public) to find relationships between clusters and these features.

---

## Outputs

- Python code for K-Means and Bisecting K-Means implementations.
- SSE values and cluster characteristics for both datasets.
- Visualizations for SSE and computation times for different `k` values.
- Summary statistics and insights from cluster analysis.

---

