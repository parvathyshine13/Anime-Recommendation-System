# 🎌 Anime Recommendation System using Cosine Similarity

## 📌 Overview
This project implements a **content-based recommendation system** that suggests similar anime titles based on their features using **cosine similarity**. The system aims to enhance user experience by offering relevant anime recommendations based on genre, ratings, and other metadata.

## 🧾 Data Description
The dataset contains detailed metadata about various anime, including:

- `anime_id`: Unique identifier for each anime
- `name`: Anime title
- `type`: Broadcast type (e.g., TV, OVA, Movie)
- `genre`: Genre tags (e.g., Action, Romance, Comedy)
- `episodes`: Number of episodes
- `rating`: Average user rating
- `members`: Number of community members interested in the anime

## 🎯 Objective
To develop a recommendation system using **cosine similarity** that suggests similar anime based on their metadata and user ratings.

## 🧹 Data Preprocessing
- Loaded the dataset using `pandas`.
- Handled missing values by imputing or removing incomplete entries.
- Explored the structure and distribution of features like genres, ratings, and episodes.

## 🧠 Feature Extraction
- Selected key features: **genres**, **user ratings**, and **number of members**.
- Converted categorical data (e.g., genre) into numerical vectors using one-hot encoding or TF-IDF.
- Normalized numerical features like ratings and member count to maintain uniformity.

## 💡 Recommendation Logic
- Computed **cosine similarity** between anime vectors based on selected features.
- Implemented a function to return a ranked list of similar anime for any given title.
- Adjusted the recommendation threshold to optimize result length and relevance.

## 🧪 Evaluation
- Split the dataset into training and test subsets.
- Evaluated performance using metrics like:
  - **Precision**
  - **Recall**
  - **F1-Score**
- Analyzed similarity accuracy and the diversity of recommended anime titles.

## 🛠 Tools & Libraries
- Python
- Pandas – Data manipulation
- Scikit-learn – Cosine similarity, evaluation metrics
- NumPy – Vectorized operations
- Jupyter Notebook – Interactive analysis

## ✅ Conclusion
- The cosine similarity-based system effectively recommends similar anime.
- With further improvements like hybrid filtering or deep learning, the system can scale to handle personalized recommendations.
- Suitable for anime streaming platforms or content aggregators.

