# 🥗 AI Diet Recommendation System

A personalized diet recommendation web application built using Python, Streamlit, Pandas, and Scikit-learn. The system suggests meals based on the user's health goals, dietary preferences, age, weight, and height.

---

## 🚀 Live Demo
Run locally using the steps below.

---

## 📸 Screenshots

> Add screenshots of your app here after running it!

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Streamlit | Interactive web interface |
| Pandas | Data processing and filtering |
| Scikit-learn | Cosine similarity recommendation engine |
| Spoonacular API | Food image fetching |

---

## ✨ Features

- 💪 Personalized diet recommendations based on health goals
- 🔍 Custom food search and recommendation
- 🤖 Hybrid recommendation engine (rule-based + ML cosine similarity)
- 🖼️ Real food images fetched via API
- 📱 Clean and interactive multi-page UI

---

## ⚙️ How to Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/Gayatribhatnagar05/diet-recommendation-system.git
cd diet-recommendation-system
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the app
```bash
python -m streamlit run Hello.py
```

### 4. Open in browser
```
http://localhost:8501
```

---

## 📁 Project Structure

```
Streamlit_Frontend/
│
├── Hello.py                          # Main entry point
├── requirements.txt                  # Dependencies
├── pages/
│   ├── 1_Diet_Recommendation.py     # Diet recommendation page
│   └── 2_Custom_Food_Recommendation.py  # Custom food page
```

---

## 🧠 How It Works

1. User enters their personal details (age, weight, height, health goal)
2. Rule-based filtering shortlists foods matching dietary needs
3. Cosine similarity algorithm ranks foods by nutritional match
4. Results are displayed with food images and nutritional info

---

## 👩‍💻 Developer

**Gayatri Bhatnagar**
- GitHub: [@Gayatribhatnagar05](https://github.com/Gayatribhatnagar05)

---

## 📄 License
This project is open source and available under the [MIT License](LICENSE).
