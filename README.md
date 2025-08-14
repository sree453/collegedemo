 🎬 Movie Recommendation System

This is a beginner-friendly Movie Recommendation System built using Python in Google Colab. It recommends movies based on content similarity using text-based features.

 📌 Project Summary

The goal of this project is to suggest similar movies based on user input. It uses **content-based filtering**, leveraging movie titles, genres, and descriptions to find similar items. This was implemented using Python libraries in Google Colab.


 🚀 Features

- Recommends movies based on content similarity
- Uses cosine similarity and TF-IDF vectorization
- Clean preprocessing of movie metadata
- Easy to modify and extend


🧰 Tech Stack

-- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn


 📁 Files Included

- `MovieRecommendationSystem.ipynb` – Main notebook with complete implementation
- `README.md` – Project description and usage guide

🧠 How It Works

1. Movie dataset is loaded and preprocessed.
2. TF-IDF vectorizer converts movie metadata into numerical vectors.
3. Cosine similarity is calculated between movies.
4. Based on a given movie, top similar movies are recommended.
5. If the person doesn't know any movies based on description we can also find the recommendation.


🧪 Example Output

> Input:Inception  
> Recommended Movies:
> - Interstellar  
> - The Matrix  
> - Shutter Island  
> - The Prestige  
> - Memento
<img width="1366" height="685" alt="Screenshot (131)" src="https://github.com/user-attachments/assets/b2cc6633-d7b0-4952-97df-a703cd67c623" />
(https://github.com/sree453/collegedemo/blob/main/result.png)

📚 Dataset Used

> Dataset Name: movies.csv
> (https://drive.google.com/file/d/1cCkwiVv4mgfl20ntgY3n4yApcWqqZQe6/view)

📌 How to Use

1. Open the notebook in [Google Colab](https://colab.research.google.com)
2. Upload or mount the dataset
3. Run the notebook cell-by-cell
4. Enter a movie name to get recommendations
5. Enter a description you can also get the recommendations

 👩‍💻 Author
Sreeja Theegala  


## 📜 License

This project is for educational purposes.

