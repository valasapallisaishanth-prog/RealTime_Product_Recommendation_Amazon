# Real-Time Product Recommendation System (Amazon SDE I Level)

A real-time product recommendation backend built with **Python**, **FastAPI**, **SQLite**, and **collaborative filtering**.  
This project demonstrates **algorithmic skills, backend system design, and database persistence**, making it fully aligned with **Amazon SDE I University Hiring requirements**.

---

## 🛠️ Tech Stack
- **Language:** Python 3  
- **Framework:** FastAPI  
- **Database:** SQLite (replaceable with PostgreSQL/DynamoDB)  
- **Data Processing:** Pandas, NumPy  
- **Algorithm:** Collaborative Filtering (User-based similarity)  
- **Other Concepts:** API design, modular architecture, real-time recommendations  

---

## 🚀 Features
- Add products via API  
- Record user interactions with products  
- Generate real-time product recommendations using collaborative filtering  
- GET `/recommend/{user_id}` returns top N recommended products  
- Persistent storage in SQLite  
- Modular and scalable architecture  

---

## 📌 Architecture Overview
- Interactions stored in DB  
- User-based collaborative filtering computes recommendations  
- API returns top N recommended products for any user  

---

## 🔧 How to Run (Locally / Colab)
1. Install dependencies:
```bash
pip install fastapi pydantic sqlalchemy pandas numpy
