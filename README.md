# Movie Recommendation System

This project implements a **Movie Recommendation System using Python in Google Colab**.  
The system recommends movies similar to a given movie using **Content-Based Filtering**.

Content-Based Filtering is a recommendation technique that uses **machine learning to suggest items based on the features (content) of those items**.

---

# Recommendation Method

**Content-Based Filtering**

This approach recommends movies by comparing their features such as:

- genres  
- keywords  
- cast  
- crew  
- overview  

The system calculates similarity between movies and suggests the most similar ones to the user.

---

# Project Notebooks

### Notebook 1 – Data Preprocessing
MinorProject1_DataPreprocessing.ipynb  

https://colab.research.google.com/drive/1b6z4UXFDypyN3F-ciYg4OujqJkRpYfPD

### Notebook 2 – Movie Recommendation
MinorProject1_Recommend.ipynb  

https://colab.research.google.com/drive/19RbdnW5SORp84oDDxxXAktwF21z_4A_N

---

# Datasets

The repository contains a **Datasets folder**.

Download the following datasets:

- `tmdb_5000_movies.csv`
- `tmdb_5000_credits.csv`

These datasets are part of the **TMDB 5000 Movie Dataset**.

---

# How to Run the Project

## Step 1 – Data Preprocessing

Open **Notebook 1 (MinorProject1_DataPreprocessing.ipynb)**.

When running the **first cell**, it will ask you to upload the datasets:

- `tmdb_5000_movies.csv`
- `tmdb_5000_credits.csv`

After preprocessing the dataset, the notebook will Download this file:

```
5000_movie_data_preprocessed.csv
```

## Step 2 – Movie Recommendation

Open **Notebook 2 (MinorProject1_Recommend.ipynb)**.

When running the first cell, upload the file:

```
5000_movie_data_preprocessed.csv
```

The notebook will then generate movie recommendations based on the input movie.

---

# Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Machine Learning (Content-Based Filtering)

---

# Project Purpose

This project was developed as part of an academic exercise to understand the working of **recommendation systems** and how machine learning techniques can be used to recommend movies based on their content.

---

# Author

**Nanda Gaddad**  
