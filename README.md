# Movie Recommendation System  

![Movie Recommendation Banner](https://via.placeholder.com/800x300?text=Movie+Recommendation+System)

> A content-based movie recommendation system using **TF-IDF Vectorization** and **Cosine Similarity** to suggest similar movies based on user input.

---

## Features  

**Content-Based Filtering** – Recommends movies based on similar genres, keywords, and cast.  
**TF-IDF Vectorization** – Converts movie descriptions into numerical feature vectors.  
**Cosine Similarity** – Computes similarity scores between movies.  
**User Input Matching** – Uses fuzzy matching to handle spelling errors in movie searches.  

---

## Installation  

### Clone the Repository  
```bash
git clone https://github.com/yourusername/movie-recommendation.git
cd movie-recommendation
```

### Create a Virtual Environment (Optional but Recommended)  
```bash
python -m venv venv
source venv/bin/activate  # For macOS/Linux
venv\Scripts\activate  # For Windows
```

### Install Dependencies  
```bash
pip install -r requirements.txt
```

---

## Dataset  

- The dataset is stored in **movies.csv**.
- Ensure that the `movies.csv` file is placed in the `data/` folder.
- If the dataset is missing, download it from [Kaggle](https://www.kaggle.com/tmdb/tmdb-movie-metadata) or use a sample dataset.

---

## Usage  

### Run the script  
```bash
python recommendation.py
```

### Example Input  
```
Enter your favorite movie: Inception
```

### Example Output  
```
Movies suggested for you:
1. Interstellar
2. The Prestige
3. Memento
...
```

---
### Evaluation Metrics
After generating recommendations, the following metrics are computed:
- **Precision@k**
- **Recall@k**
- **F1 Score@k**
- **Mean Reciprocal Rank (MRR)**

The metrics are calculated by comparing the recommended movies against a set of relevant movies or a ground truth for a group of users.

---


## Future Improvements  

🔹 Deploy as a **Flask/Streamlit Web App**  
🔹 Add **Collaborative Filtering** for hybrid recommendations  
🔹 Improve search accuracy using **Word Embeddings (BERT, Word2Vec)**  
🔹 Implement **GPU Acceleration** for large-scale similarity computations  

---


## License  

This project is licensed under the **MIT License** - feel free to use, modify, and share!  

---

## Contact  

 **Your Name**: Sudiksha Rajavaram  
