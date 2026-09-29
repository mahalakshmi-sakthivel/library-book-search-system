# 📚 Library Book Search Management System

A Streamlit web application designed for managing an in-memory library database and performing search operations across book records.

---

## Project Overview
- **Data Structure Used:** List of Dictionaries (`[{'id': int, 'title': str, 'author': str, 'genre': str}]`)
- **Search Technique:** Case-insensitive Linear Search
- **Time Complexity:** $O(n)$ (checks each record once in the worst case)
- **Space Complexity:** $O(k)$ (where $k$ is the number of matching results returned)
- **Author:** Steffi

---

## Features
- **Add Book:** Register new entries with Title, Author, and Genre. Automatically assigns unique, auto-incrementing Book IDs.
- **Display Books:** View the current catalog in a clean, responsive table with total record counts.
- **Search Book:** Find records by **Title**, **Author**, **Genre**, or **ID** using linear pattern-matching.
- **Dynamic Metrics:** Persistent sidebar tracking the total count of books in real time.

---

##  Tech Stack
- **Python 3.x**
- **Streamlit** (Web framework)

---

## Getting Started

### 1. Clone the Repository
```bash
git clone [https://github.com/mahalakshmi-sakthivel/library-book-search-system.git](https://github.com/mahalakshmi-sakthivel/library-book-search-system.git)
cd library-book-search-system

## Install dependencies
pip install -r requirements.txt

##Run the Application
streamlit run app.py

Project Structure
library-book-search-system/
│
├── app.py                # Main Streamlit application script
├── requirements.txt      # Project dependencies (streamlit)
├── .gitignore            # Ignored cache and virtual environment files
└── README.md             # Project documentation

---

### How to push this to GitHub

In your VS Code terminal, run:

```bash
git add README.md
git commit -m "docs: add comprehensive README"
git push
