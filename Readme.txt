# 🎵 Song Suggestion System using KNN

This project is a simple **music recommendation system** built using the **K-Nearest Neighbors (KNN)** algorithm. It takes a song name as input and suggests similar songs based on their audio features.

The project uses Python and Jupyter Notebook, and is ideal for those learning about basic machine learning, recommendation systems, and data preprocessing.

---

## 🧠 Features

- 📊 Uses real-world music metadata
- 🤖 Implements KNN (using `NearestNeighbors`) from scikit-learn
- 🧹 Preprocessing with Pandas and NumPy
- 🧪 Built and tested in Jupyter Notebook

---

## 📁 Files Included

- `songsuggestion.ipynb` — Main notebook for data processing, modeling, and recommendation
- `requirements.txt` *(optional)* — To install dependencies easily

---

## 📦 Installation

> Make sure Python (preferably 3.7+) is installed.

### 🔹 Step 1: Install Required Libraries

Run the following command:

```bash
pip install pandas numpy matplotlib scikit-learn

                 or
 
 If you are using requirements.txt, you can run: pip install -r requirements.txt

🔹 Step 2: Launch Jupyter Notebook

    '''bash
    jupyter notebook

Then open songsuggestion.ipynb from your browser.
🚀 How to Use

    Run all the cells in the notebook.

    Call the recommend_songs(track_name, artist_name, top_n) function with:

        track_name: Name of the song

        artist_name: (Optional) Artist name to be more specific

        top_n: Number of suggestions

🔍 Example:

recommend_songs("Shape of You", "Ed Sheeran", top=5)



Thanks for reading!❤️ by gunarajan