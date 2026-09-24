# NumPy Practice & ML-Oriented Exercises

A comprehensive **NumPy practice notebook** covering fundamental concepts, output prediction, coding implementations, data preprocessing, image-batch operations, and ML-oriented numerical computations.

This notebook is designed to strengthen practical NumPy skills required for **Python, Data Science, Machine Learning, and AI development**.

## 📌 Topics Covered

### Section A – NumPy Concepts

The notebook covers important theoretical concepts including:

* NumPy arrays vs Python lists
* Vectorization and its importance for large datasets
* Element-wise multiplication (`*`) vs matrix multiplication (`@`)
* Broadcasting
* `flatten()` vs `ravel()`
* NumPy axes (`axis=0` and `axis=1`)
* Normalization vs standardization
* Handling missing values using `np.nanmean()`
* Understanding image-array shapes
* Reproducibility using random seeds
* `np.random.default_rng()`

### Section B – Predict the Output

Practice problems focused on understanding NumPy operations and predicting their results:

* Broadcasting
* Array indexing and slicing
* Boolean/fancy indexing
* Matrix transpose
* Matrix multiplication
* Array shapes
* Reshaping
* Aggregation operations
* Other NumPy expressions

Each problem includes an explanation and corresponding NumPy implementation.

### Section C – Coding / Implementation

Practical NumPy programming tasks including:

* Exam score classification using `np.where()`
* Z-score standardization
* Combining batches using NumPy stacking
* Column-wise mean and standard deviation
* Vectorized feature standardization
* Linear-model prediction using:

```python
y_pred = X @ w + b
```

* Mean Squared Error (MSE)
* Random data generation using a fixed seed
* Min-max normalization of image pixels
* Computing average pixel values from RGB image batches

### Section D – Advanced NumPy / ML Tasks

The notebook also includes larger implementation-oriented questions covering:

* **Data Preprocessing Pipeline**

  * Detecting missing values
  * Handling `NaN` values
  * Normalization/standardization
  * Preparing data for ML models

* **Image Batch Understanding**

  * Understanding image dimensions
  * RGB image representation
  * Batch dimensions
  * Axis-based aggregation

* **Debugging Model Code**

  * Identifying errors in NumPy/ML code
  * Correcting shape and computation issues

### Section E – Additional Practice

Additional implementation problems include:

* Per-column Min-Max Normalization
* Three-Level Score Classification

---

## 🛠️ Technologies Used

* **Python**
* **NumPy**
* **Jupyter Notebook**

## 📚 NumPy Concepts Practiced

Some of the important NumPy functions and operations used in this notebook include:

```python
np.array()
np.arange()
np.reshape()
np.sum()
np.mean()
np.nanmean()
np.std()
np.min()
np.max()
np.where()
np.random.default_rng()
np.vstack()
np.ravel()
.flatten()
```

Array operations such as:

```python
*
@
+
-
/
```

along with:

* Indexing
* Slicing
* Boolean masking
* Broadcasting
* Matrix multiplication
* Vectorization
* Axis-based aggregation

---

## 🎯 Learning Objectives

After completing this notebook, you should be able to:

* Understand the advantages of NumPy for numerical computation.
* Perform efficient vectorized operations.
* Work confidently with multidimensional arrays.
* Understand NumPy broadcasting and axes.
* Manipulate and reshape arrays.
* Handle missing numerical values.
* Normalize and standardize data.
* Work with image data and batches.
* Perform basic ML-related mathematical operations.
* Generate reproducible random data.
* Debug common NumPy and shape-related errors.
* Apply NumPy concepts to data preprocessing tasks.

---

## 📂 Project Structure

```text
Sowmya_numpy/
│
├── Sowmya_numpy.ipynb
└── README.md
```

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone <your-repository-url>
```

### 2. Navigate to the project directory

```bash
cd Sowmya_numpy
```

### 3. Install NumPy

```bash
pip install numpy
```

### 4. Open the notebook

```bash
jupyter notebook Sowmya_numpy.ipynb
```

Alternatively, the notebook can be opened using **JupyterLab** or **Google Colab**.

---

## 💡 Key Takeaway

This notebook provides hands-on practice with NumPy concepts that form the foundation for **data preprocessing, machine learning, computer vision, and AI applications**.

It combines theoretical understanding with coding exercises to build practical proficiency in numerical computing with Python.

---

## 👩‍💻 Author

**Sowmya**

B.Tech – Computer Science and Engineering

Interested in **AI, Machine Learning, Python, and AI-powered applications**.
