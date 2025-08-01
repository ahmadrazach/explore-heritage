# 🗺️ ExploreHeritage — UNESCO Site Recommender

**ExploreHeritage** is a simple, lightweight web app that recommends world heritage destinations based on your input — powered by a TF-IDF text similarity engine running entirely in the browser.

> ✨ Type a natural-language query like:  
> **"mountain sites in Pakistan"** or **"ancient cities in Africa"**,  
> and get relevant UNESCO heritage site recommendations instantly.

---

## 🌍 How It Works

- Parses a CSV of UNESCO world heritage sites (via [unesco.csv](./unesco.csv)).
- Tokenizes descriptions and builds a TF-IDF vector index client-side.
- Accepts a user query, computes cosine similarity, and ranks results.
- No servers, no backend — everything runs in the browser via JavaScript.

---

## 🧪 Try It Live

Coming soon via [Vercel](https://vercel.com/) deployment.  
To test locally:

```bash
git clone https://github.com/yourusername/explore-heritage.git
cd explore-heritage
open index.html  # or just drag it into your browser
```
