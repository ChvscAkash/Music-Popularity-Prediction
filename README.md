# 🎵 Music Popularity Prediction using Machine Learning

This project applies machine learning to predict the popularity of music tracks based on their audio features and metadata. It was developed as part of an AIML assignment using a dataset of 227 songs.

---

## 📌 Project Objective
To forecast a song’s popularity using regression techniques based on features such as tempo, danceability, energy, acousticness, and more. This helps provide insights for artists, producers, and music marketers.

---

## 📁 Dataset
- Format: CSV
- Records: 227 songs
- Features: Audio metrics (tempo, energy, acousticness, etc.), release info, and popularity score
- File: `Spotify_data.csv`

---

## 🧠 Machine Learning Model
- **Algorithm:** Random Forest Regressor
- **Preprocessing:**
  - Dropped non-numeric columns
  - Converted release date to year
  - Scaled features using `StandardScaler`
- **Evaluation Metrics:**
  - Mean Squared Error (MSE)
  - R² Score

---

## 🔍 Key Findings
- **Most influential features:**  
  - `Acousticness`, `Release Year`, `Duration`

- **Outcome:**  
  The model accurately predicts popularity scores and helps identify musical traits that impact a song’s success.

---

## 📈 Visual Output
- **Correlation heatmap**
- **Feature importance bar plot**
- **Evaluation metrics displayed in output**

---

## ▶️ How to Run
1. Clone this repo or upload the files to Google Colab
2. Open `AIML_PROJECT.ipynb`
3. Upload `Spotify_data.csv` when prompted
4. Run the notebook cells to train and evaluate the model

---

## 🛠️ Tools & Libraries Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Seaborn
- Matplotlib
- Google Colab

---

## 📌 Project Outcome
> This project demonstrates how machine learning can provide actionable insights in the music industry by identifying the most influential features driving track popularity.

---

## 👨‍💻 Author
**Akash Chvsc**  
GitHub: [ChvscAkash](https://github.com/ChvscAkash)

---


