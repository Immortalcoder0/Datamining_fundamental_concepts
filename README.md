# Data Mining Lab Experiments

An elegant, hands-on collection of Python programs for core data mining concepts, built for the `Data Mining (241AI003)` course at Aditya University.

This repository is more than a set of scripts. It is a compact practical lab covering the full learning arc of data mining:

- data understanding
- preprocessing and ETL
- descriptive statistics
- classification
- association rule mining
- clustering

Each experiment is self-contained, readable, and designed to demonstrate both the concept and the workflow behind it. Most scripts print step-by-step explanations, generate visualizations, and save useful output files so the results are easy to inspect and present.

## Why This Repo Stands Out

- Clean, beginner-friendly implementations with clearly separated steps
- Covers both theory-oriented and algorithm-oriented practicals
- Uses familiar datasets like Weather and Iris alongside synthetic academic examples
- Produces charts, CSV outputs, and interpretable console results
- Great for lab submissions, viva preparation, revision, and self-study

## Experiment Map

| No. | File | Topic | What it demonstrates |
| --- | --- | --- | --- |
| 1 | `exp1_kdd_process.py` | KDD Process | Selection, cleaning, transformation, classification, evaluation, and presentation in a single mini-pipeline |
| 2 | `exp2_etl_process.py` | ETL Process | Extracting from multiple sources, transforming records, joining tables, and loading warehouse-style CSV outputs |
| 3 | `exp3_statistical_measures.py` | Statistical Description | Descriptive statistics plus similarity and dissimilarity measures using the Iris dataset |
| 4 | `exp4_weather_preprocessing.py` | Data Preprocessing | Missing values, duplicates, attribute removal, normalization, standardization, and outlier detection |
| 5 | `exp5_id3_algorithm.py` | ID3 Classification | Entropy, information gain, rules, and decision-tree visualization on the weather dataset |
| 6 | `exp6_j48_decision_tree.py` | J48 Classification | Decision-tree based academic performance classification with evaluation metrics and cross-validation |
| 7 | `exp7_apriori_algorithm.py` | Apriori | Frequent itemsets, support, confidence, lift, and business interpretation from transaction data |
| 8 | `exp8_fpgrowth_algorithm.py` | FP-Growth | Frequent pattern mining and association rule generation using the contact lenses dataset |
| 9 | `exp9_kmeans_clustering.py` | K-Means Clustering | Elbow method, centroids, cluster metrics, and visual cluster interpretation |
| 10 | `exp10_hierarchical_clustering.py` | Hierarchical Clustering | Linkage comparison, dendrogram analysis, cluster evaluation, and interpretation |

## Tech Stack

- Python
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- scipy

## Quick Start

### 1. Clone the repository

```bash
git clone <your-repo-url>
cd fds
```

### 2. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy
```

### 3. Run any experiment

```bash
python exp1_kdd_process.py
python exp5_id3_algorithm.py
python exp9_kmeans_clustering.py
```

## Outputs You Can Expect

Depending on the script, the repository can generate:

- `.png` charts and plots
- `.csv` processed datasets and summary tables
- printed metrics such as accuracy, support, confidence, lift, silhouette score, and Davies-Bouldin index
- decision rules and interpretable summaries for reports or presentations

Examples of generated files include:

- `exp1_kdd_output.png`
- `fact_sales.csv`
- `dim_customer.csv`
- `agg_product_sales.csv`
- `weather_preprocessed.csv`
- `exp5_id3_output.png`
- `exp9_kmeans_output.png`
- `exp10_hierarchical_output.png`

## Learning Journey Through the Repo

If you want to study this repository in a smooth order, use this path:

1. Start with `exp1_kdd_process.py` to understand the end-to-end data mining pipeline.
2. Move to `exp2_etl_process.py` and `exp4_weather_preprocessing.py` to build data preparation intuition.
3. Use `exp3_statistical_measures.py` to strengthen descriptive analysis and distance concepts.
4. Study `exp5_id3_algorithm.py` and `exp6_j48_decision_tree.py` for classification.
5. Continue with `exp7_apriori_algorithm.py` and `exp8_fpgrowth_algorithm.py` for pattern mining.
6. Finish with `exp9_kmeans_clustering.py` and `exp10_hierarchical_clustering.py` for clustering techniques.

## Best Use Cases

This repository is especially useful for:

- B.Tech or undergraduate data mining lab work
- practical exam revision
- preparing record submissions
- understanding classic algorithms through small, readable examples
- creating presentation-ready experiment output quickly

## Notes

- Most datasets are embedded directly in the scripts for easy execution.
- Several experiments use classic benchmark-style datasets such as Iris and Weather.
- Visual outputs are saved automatically in the project directory.
- Some plots open interactively with `matplotlib`, so running them in a Python environment with display support is ideal.

## Suggested Future Upgrades

If you want to evolve this project even further, strong next additions would be:

- a `requirements.txt`
- sample screenshots of generated plots in the README
- command-line arguments for experiment parameters
- a unified `outputs/` folder for generated artifacts
- Jupyter notebook versions of each experiment

## Repository Identity

This project captures the spirit of a strong academic lab repository: practical, demonstrative, and easy to learn from. It is small enough to understand quickly, but broad enough to showcase the backbone of data mining in one place.

## License

Add a license if you want to make reuse and sharing explicit.
