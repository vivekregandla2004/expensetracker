# Expense Tracker

A simple and clean **Expense Tracker** web application built with **Django + Python + SQL** to help users track daily spending, categorize expenses, and view monthly summaries.

---

## 🚀 Features

- User Authentication (Login / Logout)
- Add, Edit, Delete Expenses
- Category-wise Expense Tracking
- Monthly Summary View
- Clean UI with responsive layout
- Secure data handling

---

## 🛠 Tech Stack

- **Backend:** Django, Python  
- **Database:** SQLite (default) / MySQL / PostgreSQL  
- **Frontend:** HTML, CSS, Bootstrap (optional)  
- **Version Control:** Git, GitHub  

---

## 📂 Project Structure (Basic)

```
expense-tracker/
│── manage.py
│── requirements.txt
│── db.sqlite3
│── <app_name>/
│── templates/
│── static/
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/vivekregandla2004/expense-tracker.git
cd expense-tracker
```

### 2️⃣ Create and activate virtual environment
```bash
python -m venv venv
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate
```

### 3️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Apply migrations
```bash
python manage.py makemigrations
python manage.py migrate
```

### 5️⃣ Create superuser (optional)
```bash
python manage.py createsuperuser
```

### 6️⃣ Run the server
```bash
python manage.py runserver
```

Open in browser:
```
http://127.0.0.1:8000/
```

---

## 📊 Example Use Cases

- Track daily spending (Food, Travel, Shopping, etc.)
- Monitor monthly expenses and budget patterns
- Generate insights on top spending categories

---

## ✅ Future Enhancements (Optional)

- Budget alerts (80% / 100% usage notifications)
- Expense charts (Pie / Bar graphs)
- CSV/PDF export of monthly report
- Multi-currency support
- Mobile-friendly UI improvements

---

## 👨‍💻 Author

**Sai Vivek Regandla**  
📧 Email: 2200032415cseh@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/sai-vivek-regandla/  

---

## 📄 License

This project is for learning and educational purposes.
