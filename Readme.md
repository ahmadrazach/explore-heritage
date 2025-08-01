# 🗺️ ExploreHeritage — UNESCO Site Recommender

This is a lightweight, fully client-side web application that uses **TF-IDF** (Term Frequency-Inverse Document Frequency) and **Cosine Similarity** to recommend travel destinations based on user queries.

> ✨ Type a natural-language query like:  
> **"mountain sites in Pakistan"** or **"ancient cities in Africa"**,  
> and get the top UNESCO World Heritage destinations that best match the intent of their search.

[demo](https://screenrec.com/share/W4MPCBaVfE) 
---

## 🌍 How It Works

- The app uses [`unesco.csv`](./unesco.csv), which includes UNESCO World Heritage site metadata (name, country, category).
- The text from each site is vectorized using the **TF-IDF** method.
- A **Cosine Similarity** score is computed between the query and each site vector.
- The top 5 most relevant matches are returned and ranked in the table.

---

## 📊 Technologies Used

| Feature                | Tool/Method            |
| ---------------------- | ---------------------- |
| Text Vectorization     | TF-IDF                 |
| Similarity Calculation | Cosine Similarity      |
| CSV Parsing            | PapaParse.js (browser) |
| Frontend               | HTML + Vanilla JS      |
| Hosting (Suggested)    | GitHub + Vercel        |

---

## 📁 File Structure

travel_recommender/
├── index.html # Main app logic and UI
├── unesco.csv # UNESCO dataset (parsed in-browser via PapaParse)
└── templates/ # Flask backend templates (optional for extension)
└── index.html # HTML template (unused in pure frontend mode)

---

## 🧪 Try It Live

live demo link : https://explore-heritage.vercel.app/

To test locally:

```bash
git clone https://github.com/ahmadrazach/explore-heritage.git
cd explore-heritage
open index.html  # or just drag it into your browser
```
