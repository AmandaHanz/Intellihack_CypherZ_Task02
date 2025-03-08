# Customer Segmentation Project

This project performs customer segmentation using K-Means and Gaussian Mixture Models (GMM) on a customer behavior dataset. The goal is to identify distinct customer segments based on their purchasing behavior, browsing activity, and discount usage patterns.

## Project Overview

The project follows these key steps:
1. **Data Loading:** Load the dataset from a CSV file.
2. **Data Preprocessing:** Handle missing values, cap outliers, and standardize features.
3. **Feature Engineering:** Create new features to capture nuanced customer behaviors.
4. **Exploratory Data Analysis (EDA):** Visualize feature distributions and relationships.
5. **Model Selection:** Implement K-Means and GMM clustering.
6. **Model Evaluation:** Evaluate models using Silhouette Score, Davies-Bouldin Index, and Calinski-Harabasz Index.
7. **Cluster Identification:** Assign meaningful labels to clusters and visualize using PCA and t-SNE.
8. **Export Results:** Save the final DataFrame with cluster assignments to a CSV file.

## Setup Instructions

### Prerequisites
- Python 3.8+
- Required libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, scipy

### Installation
1. **Clone the repository:**
```bash
git clone https://github.com/yourusername/customer-segmentation-project.git
cd customer-segmentation-project
```

2. **Create a virtual environment:**
```bash
python3 -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

3. **Add the dataset:**
Place the dataset (`customer_behavior_analytics.csv`) in the `data` directory.

### Running the Project

1. **Run the clustering script:**
```bash
python customer_segmentation.py
```

2. **View Results:**
The output file `customer_segments_output.csv` will be generated in the project directory.

### Repository Structure
```
customer-segmentation-project/
├── data/
│   └── customer_behavior_analytics.csv
├── src/
│   └── customer_segmentation.py
├── requirements.txt
├── README.md
└── customer_segments_output.csv
```

### Contributing
Feel free to submit issues or pull requests. Contributions are welcome!

### License
This project is licensed under the MIT License.

