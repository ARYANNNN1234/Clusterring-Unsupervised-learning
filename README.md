# Clustering and Dimensionality Reduction Streamlit App

## Overview
This interactive Streamlit application provides a hands-on demonstration of fundamental unsupervised machine learning techniques: **K-Means Clustering**, **DBSCAN**, and **Principal Component Analysis (PCA)**. Users can generate synthetic 2D datasets, adjust algorithm parameters, and visualize clustering and dimensionality reduction results in real-time.

---

## Features

- **Dataset Generation:** Choose between 'Blobs' (Gaussian distributions) and 'Moons' (non-linearly separable) synthetic datasets.
- **Parameter Control:** Adjust number of samples, cluster count/noise, K-Means 'K' value, DBSCAN 'eps' and 'min_samples'.
- **K-Means Clustering:** Visualize clusters formed by the K-Means algorithm.
- **DBSCAN Clustering:** Explore density-based clustering, including noise points.
- **Principal Component Analysis (PCA):** Reduce dimensionality to 2 principal components and visualize explained variance.
- **Interactive Visualizations:** All results are displayed using matplotlib and seaborn scatter plots, dynamically updating with parameter changes.

---

## How to Run the Application

### 1. Save the Code
Save the provided Streamlit code as a Python file (e.g., `clustering_app.py`).

### 2. Install Dependencies

```sh
pip install streamlit pandas numpy scikit-learn matplotlib seaborn
```

### 3. Run the App

```sh
streamlit run clustering_app.py
```

### 4. Access the App
Your default browser will open the Streamlit application, usually at [http://localhost:8501](http://localhost:8501). Use the sliders and select boxes to interactively explore the algorithms.

---

## Project Files

- `clustering_app.py`: The main Streamlit application code.

---

## Technologies Used
- Python
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## Future Enhancements

- Add the "Elbow Method" plot for K-Means to guide optimal K selection.
- Allow users to upload their own 2D datasets.
- Implement additional clustering algorithms (e.g., Agglomerative Clustering).
- Provide more detailed metrics for clustering evaluation (e.g., Silhouette Score).

---



## Contact
For questions or suggestions, please open an issue or contact [repo owner](https://github.com/ARYANNNN1234).
