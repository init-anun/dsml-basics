# Data Science and Machine Learning (DSML) Fundamentals

Welcome to the **Data Science and Machine Learning Fundamentals** repository! This project serves as a comprehensive, structured curriculum designed to take you from a complete beginner to a confident practitioner in DSML using the Python scientific computing ecosystem.

Each module contains self-paced Jupyter Notebooks containing core concepts, code walkthroughs, visual demonstrations, and practical exercises.

---

## 🛠️ Getting Started & Installation

To run these notebooks locally, it is recommended to set up an isolated Python environment using **Anaconda** or **miniconda**.

### 1. Clone the Repository
```bash
git clone https://github.com/init-anun/dsml-fundamentals.git
cd dsml-fundamentals
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

## 📅 Curriculum & Directory Map

Below is a breakdown of all topics covered in this repository. You can click on the directory links to access each module's notebooks:

| Module | Core Topics |
| :--- | :--- |
| **01. NumPy Basics**<br>↳ [01-numpy](./01-numpy) | N-dimensional arrays, indexing, selection, broadcasting, and vector operations. |
| **02. Pandas Data Analysis**<br>↳ [02-pandas](./02-pandas) | Series, DataFrames, cleaning missing data, GroupBy, Merging/Joining, and built-in I/O (CSV, Excel, SQL). |
| **03. Scientific Computing with SciPy**<br>↳ [03-scipy](./03-scipy) | Integration, optimization, linear algebra, and signal processing. |
| **04. Data Visualization**<br>↳ [04-data-viz](./04-data-viz) | Matplotlib, Seaborn (distributional, categorical, matrix, grids, regression plots), Pandas built-in plots, and interactive Plotly/Cufflinks. |
| **05. Exploratory Data Analysis (EDA)**<br>↳ [05-eda](./05-eda) | Conducting end-to-end exploratory data analysis on real-world datasets. |
| **06. Linear Regression**<br>↳ [06-linear-regression](./06-linear-regression) | Fundamentals of Ordinary Least Squares (OLS) regression, modeling features, and predicting housing/ecommerce metrics. |
| **07. Logistic Regression**<br>↳ [07-logistic-regression](./07-logistic-regression) | Binary classification, sigmoid function, decision boundaries, classification reports, and confusion matrices. |
| **08. K-Nearest Neighbors (KNN)**<br>↳ [08-k-near-neighbors](./08-k-near-neighbors) | Distance-based classification, feature scaling, and choosing the optimal K-value using the elbow method. |
| **09. Decision Trees & Random Forests**<br>↳ [09-decision-trees-random-forests](./09-decision-trees-random-forests) | Tree-based models, entropy/information gain, bagging, and ensemble learning methods. |
| **10. Support Vector Machines (SVM)**<br>↳ [10-support-vector-machines](./10-support-vector-machines) | Margin optimization, kernel trick (RBF, linear, poly), and hyperparameter tuning with GridSearchCV. |
| **11. K-Means Clustering**<br>↳ [11-k-means-clustering](./11-k-means-clustering) | Unsupervised learning, centroid-based clustering, and the elbow method to find clusters. |
| **12. Principal Component Analysis (PCA)**<br>↳ [12-principal-component-analysis](./12-principal-component-analysis) | Dimensionality reduction, variance retention, and feature orthogonalization. |
| **13. Recommender Systems**<br>↳ [13-recommender-systems](./13-recommender-systems) | Collaborative filtering, content-based filtering, and similarity metrics (Pearson correlation, cosine similarity). |
| **14. Natural Language Processing (NLP)**<br>↳ [14-nlp](./14-nlp) | Text preprocessing, tokenization, TF-IDF, bag-of-words model, and Naive Bayes classifiers for spam detection. |
| **15. Big Data & Spark**<br>↳ [15-big-data-and-spark](./15-big-data-and-spark) | Introduction to Apache Spark ecosystem, PySpark RDD transformations (map, filter), and actions (collect, count). |
| **16. Deep Learning**<br>↳ [16-deep-learning](./16-deep-learning) | Artificial Neural Networks (ANNs), backpropagation, TensorFlow Estimators, MNIST image classification, and custom Keras models. |

---

## 📈 Learning Path Recommendation

If you are new to Data Science and Machine Learning, here is the recommended sequence to progress through the repository:

1. **Foundations**: Start with `01-numpy`, `02-pandas`, and `03-scipy` to get comfortable manipulating data.
2. **Visualization & Exploration**: Move to `04-data-viz` and practice EDA in `05-eda`.
3. **Supervised Machine Learning**:
   - Begin with Regression: `06-linear-regression` and `07-logistic-regression`.
   - Explore classification and distance/tree algorithms: `08-k-near-neighbors`, `09-decision-trees-random-forests`, and `10-support-vector-machines`.
4. **Unsupervised Learning & Advanced Topics**:
   - Master Clustering and Dimensionality Reduction: `11-k-means-clustering` and `12-principal-component-analysis`.
   - Learn personalization engines: `13-recommender-systems`.
5. **Specialized Domains & Big Data**:
   - Process unstructured text with `14-nlp`.
   - Understand distributed computing with `15-big-data-and-spark`.
   - Dive into neural networks with `16-deep-learning`.

---

