# Netflix Movies and TV Shows Clustering — Capstone Project

## 📁 Folder Structure
```
netflix_clustering_project/
├── README.md                                  ← Ye file
├── SUBMISSION_CHECKLIST.md                    ← Submission se pehle ki checklist
├── VIDEO_SCRIPT.md                            ← Video presentation ke liye script/outline
├── requirements.txt                           ← Python libraries list
├── data/
│   ├── netflix_titles.csv                     ← Original raw dataset
│   └── netflix_titles_cleaned.csv             ← Cleaned dataset (notebook run ke baad generate hota hai)
├── notebooks/
│   └── Netflix_Clustering_ML_Submission.ipynb ← MAIN NOTEBOOK (submit karne wali file)
└── models/
    ├── kmeans_model.joblib                    ← Trained clustering model
    ├── tfidf_vectorizer.joblib                ← Trained TF-IDF vectorizer
    └── svd_transformer.joblib                 ← Trained dimensionality reduction model
```

## ✅ Project Kya Hai
Netflix ke 2019 tak ke Movies/TV Shows dataset par:
1. Exploratory Data Analysis (15 charts + insights)
2. 3 Hypothesis Tests (statistical validation)
3. Text preprocessing + TF-IDF feature engineering
4. Unsupervised Clustering — K-Means aur Agglomerative Hierarchical Clustering (dono compare kiye gaye)
5. Cluster explainability aur business use-case

Notebook **already fully executed hai — 0 errors**, saare charts aur outputs already saved hain notebook ke andar. Tumhe bas isse open karke dekhna hai.

## 🚀 Notebook Ko Kaise Chalayein (Agar tum khud se re-run karna chaho)

1. Requirements install karo:
   ```
   pip install -r requirements.txt
   ```
2. `notebooks/Netflix_Clustering_ML_Submission.ipynb` ko Jupyter/Colab mein open karo
3. Run All karo (agar Google Colab use kar rahe ho, to `data/netflix_titles.csv` ko upload karke path `../data/netflix_titles.csv` ko `netflix_titles.csv` se replace kar dena, ya Colab mein `/content/netflix_titles.csv` use karo)

## 📝 Tumhe Khud Kya Karna Hai (Submission ke liye)

1. **Apna naam** notebook ke top wale markdown cell mein likho (jahan "[Apna Naam Yahan Likhein]" likha hai)
2. **GitHub repo** banao, is poore folder ko usme push karo, aur GitHub link ko notebook ke "GitHub Link" section mein daalo
3. Ek **Google Drive folder** banao jiski access "Anyone with the link" ho
4. Us folder mein 2 files daalo:
   - Filled `.ipynb` notebook
   - Apni **video recording** (7-30 min, khud ka explanation)
5. Video record karte waqt `VIDEO_SCRIPT.md` follow karo
6. Google Form fill karke drive link submit karo — **Deadline: 23rd Oct 2025**

## ⚠️ Important Note
Is project mein **synthetic/dummy data nahi hai** — yeh wahi standard "Netflix Movies and TV Shows" dataset hai jo project brief mein describe kiya gaya tha (Flixable se collected, 2019 tak ka data), jo publicly GitHub par mirror available hai kyunki tumhare diye gaye Google Drive link ko is environment se access nahi kiya ja saka (network restriction). Agar tumhare paas apna original Drive dataset hai, to bas usse `data/netflix_titles.csv` se replace kar dena — column names same hain (`show_id, type, title, director, cast, country, date_added, release_year, rating, duration, listed_in, description`), to notebook bina kisi change ke chalega.
