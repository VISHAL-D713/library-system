# 📚 Library Book Search System

A web-based **Library Management & Book Search System** built using **Flask (Python)** and **Data Structures & Algorithms (DSA)** like **Binary Search Tree (BST)** and **Stack** to store and search books efficiently.

---

## Features

-  Add new books  
-  Search books using **Binary Search Tree (BST)**  
-  Display all books in sorted order  
-  Uses **Stack** for search history (if implemented)  
-  User-friendly UI using Flask Templates (HTML + CSS)

---

## 📂 Project Structure

```

Library-Book-Search-System/
│── app.py                 # Main Flask application
│── bst.py                 # Binary Search Tree logic
│── stack.py               # Stack data structure
│── dsamini/               # Additional Python modules
│── templates/             # HTML templates (frontend)
│── static/                # CSS, JS, images
│── **pycache**/           # Auto-generated files (ignored)
│── README.md              # Project documentation

````

---

## Technologies Used

| Technology | Purpose |
|------------|---------|
| Python     | Backend logic |
| Flask      | Web framework |
| HTML / CSS | Frontend pages |
| BST & Stack| Searching and storing data |
| Git & GitHub | Version control |

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/chetanhire66/Library-Book-Search-System.git
cd Library-Book-Search-System
````

### 2️⃣ (Optional) Create Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate       # On Windows
# OR
source venv/bin/activate    # On Mac/Linux
```

### 3️⃣ Install Dependencies

```bash
pip install flask
# or
pip install -r requirements.txt
```

### 4️⃣ Run the Flask Application

```bash
python app.py
# or
flask run
```

Then open your browser and go to:
👉 **[http://127.0.0.1:5000/](http://127.0.0.1:5000/)**

---

## How It Works

* Books are stored using a **Binary Search Tree (BST)** for faster searching.
* **Stack** is used to store search history or undo operations.
* Flask manages the connection between **frontend (HTML/CSS)** and **backend (Python + DSA)**.

---

## Future Enhancements

* Add edit/delete book options
* Connect with a database (SQLite / MySQL)
* Add login system (Admin/Student)
* Deploy on Render / Railway / Heroku

---

## Developed By

**Chetan Hire**
GitHub: [@chetanhire66](https://github.com/chetanhire66)

---

## ⭐ How to Contribute

1. Fork this repository
2. Create a new branch
3. Make your changes
4. Submit a pull request


---

✅ **Now you can copy and paste this directly into README.md on GitHub.**  
Want me to generate `.gitignore` or `requirements.txt` also? 😊
My name is Vishal this was intro to git and github
```
