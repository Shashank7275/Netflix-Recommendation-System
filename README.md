
# 🎬 Netflix Recommendation System

A movie recommendation system that suggests similar films based on user input, inspired by Netflix’s recommendation logic.

## 🚀 Features
- Content-based movie recommendations  
- Uses cosine similarity for finding similar movies  
- Interactive user interface with Streamlit  
- Fast and lightweight  

## 🧩 Tech Stack
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Streamlit  

## ⚙️ How It Works
1. The dataset is processed to extract information like genre, cast, and description.  
2. Text data is vectorized using CountVectorizer or TF-IDF.  
3. Cosine similarity is calculated between movies.  
4. When a user enters a movie name, the system shows the top similar movies.  

## 🖥️ Run Locally
```bash
git clone https://github.com/your-username/netflix-recommendation-system.git
cd netflix-recommendation-system
pip install -r requirements.txt
streamlit run app.py
````

## 📁 Project Structure

```
netflix-recommendation-system/
│
├── app.py
├── movies.pkl
├── similarity.pkl
├── requirements.txt
├── README.md
└── dataset/
```

## 🎯 Future Enhancements

* Add collaborative filtering
* Connect with TMDB API for live data
* Improve UI design

## 👨‍💻 Author

**Shashank Singh**
Built with ❤️ using Python and Streamlit.

