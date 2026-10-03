# Movie Recommendation System

A mini machine learning project that recommends movies similar to a movie selected by the user. The system uses a **content-based filtering approach**, comparing movie features to find the most similar titles.

-------Features-------------------------------------

- Movie-based recommendations
- Content-based filtering
- Feature extraction from movie metadata
- Cosine similarity for finding similar movies

-------How It Works---------------------------------

The system combines relevant movie features such as:

- Genres
- Keywords
- Cast
- Director
- Overview

These features are processed and converted into numerical vectors. **Cosine similarity** is then used to compare movies and generate recommendations.

```text
Movie Dataset
      ↓
Data Preprocessing
      ↓
Feature Extraction
      ↓
Vectorization
      ↓
Cosine Similarity
      ↓
Recommended Movies
