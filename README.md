# Data Science and Machine Learning (DSML) Basics

Welcome to the **Data Science and Machine Learning Basics** repository! This project serves as a comprehensive, structured curriculum designed to take you from a complete beginner to a confident practitioner in DSML using the Python scientific computing ecosystem.

Each module contains self-paced Jupyter Notebooks containing core concepts, code walkthroughs, visual demonstrations, and practical exercises.

---

## 🛠️ Getting Started & Installation

To run these notebooks locally, it is recommended to set up an isolated Python environment using **Anaconda** or **miniconda**.

### 1. Clone the Repository
```bash
git clone https://github.com/init-anun/dsml-basics.git
cd dsml-basics
```

### 2. Create and Activate a Virtual Environment
Create a new conda environment with Python 3.10+:
```bash
conda create -n dsml-env python=3.10 -y
conda activate dsml-env
```

### 3. Install Dependencies
Install all required libraries for data processing, plotting, machine learning, and deep learning:
```bash
pip install numpy pandas matplotlib seaborn scipy scikit-learn plotly cufflinks nltk tensorflow pyspark jupyter
```

### 4. Launch Jupyter Notebook
Run the notebook server from the root directory:
```bash
jupyter notebook
```

---

## 📅 Curriculum & Notebook Directory Map

Below is a breakdown of all topics covered in this repository. You can click on the directory or notebook links to access them directly:

| Module | Core Topics | Notebook Links |
| :--- | :--- | :--- |
| **01. NumPy Basics**<br>↳ [01-numpy](./01-numpy) | N-dimensional arrays, indexing, selection, broadcasting, and vector operations. | • [arrays.ipynb](./01-numpy/arrays.ipynb)<br>• [indexing-and-selection.ipynb](./01-numpy/indexing-and-selection.ipynb)<br>• [operations.ipynb](./01-numpy/operations.ipynb)<br>• [additional.ipynb](./01-numpy/additional.ipynb) |
| **02. Pandas Data Analysis**<br>↳ [02-pandas](./02-pandas) | Series, DataFrames, cleaning missing data, GroupBy, Merging/Joining, built-in I/O (CSV, Excel, SQL). | • [series.ipynb](./02-pandas/series.ipynb)<br>• [dataframes.ipynb](./02-pandas/dataframes.ipynb)<br>• [missing-data.ipynb](./02-pandas/missing-data.ipynb)<br>• [groupby.ipynb](./02-pandas/groupby.ipynb)<br>• [merging-joining-concatenating.ipynb](./02-pandas/merging-joining-concatenating.ipynb)<br>• [operations.ipynb](./02-pandas/operations.ipynb)<br>• [data-input-output.ipynb](./02-pandas/data-input-output.ipynb)<br>• [ecommerce-purchases.ipynb](./02-pandas/additional/ecommerce-purchases.ipynb)<br>• [sf-salaries.ipynb](./02-pandas/additional/sf-salaries.ipynb) |
| **03. Scientific Computing with SciPy**<br>↳ [scipy](./scipy) | Integration, optimization, linear algebra, and signal processing. | • [scipy.ipynb](./scipy/scipy.ipynb) |
| **04. Data Visualization**<br>↳ [03-data-viz](./03-data-viz) | Matplotlib, Seaborn (distributional, categorical, matrix, grids, regression plots), Pandas built-in plots, and interactive Plotly/Cufflinks. | **Matplotlib:**<br>• [concepts.ipynb](./03-data-viz/matplotlib/concepts.ipynb)<br>• [advanced-concepts.ipynb](./03-data-viz/matplotlib/advanced-concepts.ipynb)<br>• [examples.ipynb](./03-data-viz/matplotlib/examples.ipynb)<br>**Seaborn:**<br>• [distribution-plots.ipynb](./03-data-viz/seaborn/distribution-plots.ipynb)<br>• [categorical-plots.ipynb](./03-data-viz/seaborn/categorical-plots.ipynb)<br>• [matrix-plots.ipynb](./03-data-viz/seaborn/matrix-plots.ipynb)<br>• [grids.ipynb](./03-data-viz/seaborn/grids.ipynb)<br>• [regression-plots.ipynb](./03-data-viz/seaborn/regression-plots.ipynb)<br>• [style-and-color.ipynb](./03-data-viz/seaborn/style-and-color.ipynb)<br>• [example.ipynb](./03-data-viz/seaborn/example.ipynb)<br>**Pandas Built-in & Plotly:**<br>• [concepts.ipynb](./03-data-viz/pandas-built-in/concepts.ipynb)<br>• [example.ipynb](./03-data-viz/pandas-built-in/example.ipynb)<br>• [plotly-and-cufflinks.ipynb](./03-data-viz/plotly-and-cufflinks/plotly-and-cufflinks.ipynb)<br>**Geographical Plotting:**<br>• [concepts.ipynb](./03-data-viz/geographical-plotting/concepts.ipynb)<br>• [example.ipynb](./03-data-viz/geographical-plotting/example.ipynb) |
| **05. Exploratory Data Analysis (EDA)**<br>↳ [04-eda](./04-eda) | Conducting end-to-end exploratory data analysis on real-world datasets. | • [calls-data.ipynb](./04-eda/calls-data.ipynb)<br>• [finance.ipynb](./04-eda/finance.ipynb) |
| **06. Linear Regression**<br>↳ [05-linear-regression](./05-linear-regression) | Fundamentals of Ordinary Least Squares (OLS) regression, modeling features, and predicting housing/ecommerce metrics. | • [housing-price.ipynb](./05-linear-regression/housing-price.ipynb)<br>• [california.ipynb](./05-linear-regression/california.ipynb)<br>• [ecommerce.ipynb](./05-linear-regression/ecommerce.ipynb) |
| **07. Logistic Regression**<br>↳ [06-logistic-regression](./06-logistic-regression) | Binary classification, sigmoid function, decision boundaries, classification reports, and confusion matrices. | • [concept.ipynb](./06-logistic-regression/concept.ipynb)<br>• [example.ipynb](./06-logistic-regression/example.ipynb) |
| **08. K-Nearest Neighbors (KNN)**<br>↳ [07-k-near-neighbors](./07-k-near-neighbors) | Distance-based classification, feature scaling, choosing the optimal K-value using the elbow method. | • [concepts.ipynb](./07-k-near-neighbors/concepts.ipynb)<br>• [example.ipynb](./07-k-near-neighbors/example.ipynb) |
| **09. Decision Trees & Random Forests**<br>↳ [08-decision-trees-random-forests](./08-decision-trees-random-forests) | Tree-based models, entropy/information gain, bagging, and ensemble learning methods. | • [concepts.ipynb](./08-decision-trees-random-forests/concepts.ipynb)<br>• [example.ipynb](./08-decision-trees-random-forests/example.ipynb) |
| **10. Support Vector Machines (SVM)**<br>↳ [09-support-vector-machines](./09-support-vector-machines) | Margin optimization, kernel trick (RBF, linear, poly), and hyperparameter tuning with GridSearchCV. | • [concepts.ipynb](./09-support-vector-machines/concepts.ipynb)<br>• [example.ipynb](./09-support-vector-machines/example.ipynb) |
| **11. K-Means Clustering**<br>↳ [10-k-means-clustering](./10-k-means-clustering) | Unsupervised learning, centroid-based clustering, and the elbow method to find clusters. | • [concepts.ipynb](./10-k-means-clustering/concepts.ipynb)<br>• [example.ipynb](./10-k-means-clustering/example.ipynb) |
| **12. Principal Component Analysis (PCA)**<br>↳ [11-principal-component-analysis](./11-principal-component-analysis) | Dimensionality reduction, variance retention, and feature orthogonalization. | • [concepts.ipynb](./11-principal-component-analysis/concepts.ipynb) |
| **13. Recommender Systems**<br>↳ [12-recommender-systems](./12-recommender-systems) | Collaborative filtering, content-based filtering, and similarity metrics (Pearson correlation, cosine similarity). | • [recommender-systems.ipynb](./12-recommender-systems/recommender-systems.ipynb)<br>• [advanced-recommender-systems.ipynb](./12-recommender-systems/advanced-recommender-systems.ipynb) |
| **14. Natural Language Processing (NLP)**<br>↳ [13-nlp](./13-nlp) | Text preprocessing, tokenization, TF-IDF, bag-of-words model, and Naive Bayes classifiers for spam detection. | • [concepts.ipynb](./13-nlp/concepts.ipynb)<br>• [example.ipynb](./13-nlp/example.ipynb) |
| **15. Big Data & Spark**<br>↳ [14-big-data-and-spark](./14-big-data-and-spark) | Intro to Apache Spark ecosystem, PySpark RDD transformations (map, filter) and actions (collect, count). | • [introduction-to-spark.ipynb](./14-big-data-and-spark/introduction-to-spark.ipynb)<br>• [rdd-transformations-and-actions.ipynb](./14-big-data-and-spark/rdd-transformations-and-actions.ipynb) |
| **16. Deep Learning**<br>↳ [15-deep-learning](./15-deep-learning) | Artificial Neural Networks (ANNs), backpropagation, TensorFlow Estimators, MNIST image classification, and custom Keras models. | • [basics.ipynb](./15-deep-learning/basics.ipynb)<br>• [tensorflow-with-estimators.ipynb](./15-deep-learning/tensorflow-with-estimators.ipynb)<br>• [MNIST-with-Tensorflow.ipynb](./15-deep-learning/MNIST-with-Tensorflow.ipynb)<br>• [example-project.ipynb](./15-deep-learning/example-project.ipynb) |

---

## 📈 Learning Path Recommendation

If you are new to Data Science and Machine Learning, here is the recommended sequence to progress through the repository:

1. **Foundations**: Start with `01-numpy`, `02-pandas`, and `scipy` to get comfortable manipulating data.
2. **Visualization & Exploration**: Move to `03-data-viz` and practice EDA in `04-eda`.
3. **Supervised Machine Learning**:
   - Begin with Regression: `05-linear-regression` and `06-logistic-regression`.
   - Explore classification and distance/tree algorithms: `07-k-near-neighbors`, `08-decision-trees-random-forests`, and `09-support-vector-machines`.
4. **Unsupervised Learning & Advanced Topics**:
   - Master Clustering and Dimensionality Reduction: `10-k-means-clustering` and `11-principal-component-analysis`.
   - Learn personalization engines: `12-recommender-systems`.
5. **Specialized Domains & Big Data**:
   - Process unstructured text with `13-nlp`.
   - Understand distributed computing with `14-big-data-and-spark`.
   - Dive into neural networks with `15-deep-learning`.

---

## 📝 License
This project is open-source and available under the MIT License. Feel free to use these notebooks for learning and educational purposes!
