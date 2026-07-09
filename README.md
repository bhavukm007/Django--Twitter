# 🐦 Django Twitter Clone

A feature-rich Twitter clone built using **Django** and **Bootstrap**, allowing users to register, authenticate, create tweets with images, and manage their own posts.

---

## 📖 Overview

This project demonstrates the implementation of a complete CRUD web application using Django's built-in authentication system. Users can create accounts, log in securely, upload tweets with images, edit or delete their own tweets, and browse tweets posted by all users.

---

## ✨ Features

- 🔐 User Registration & Login
- 👤 User Authentication using Django Auth
- 📝 Create Tweets
- 🖼️ Upload Images with Tweets
- ✏️ Edit Your Own Tweets
- 🗑️ Delete Your Own Tweets
- 📋 View All Tweets
- 🎨 Responsive UI with Bootstrap
- 📁 Media File Handling
- 🔒 Authorization (Users can only edit/delete their own tweets)

---

# 📸 Screenshots

## Home Page

![alt text](<Screenshot 2026-07-09 194827.png>)

---

## Registration Page

![alt text](<Screenshot 2026-07-09 194842.png>)

---

# 🛠 Tech Stack

- **Backend:** Django 5/6
- **Frontend:** HTML, CSS, Bootstrap 5
- **Database:** SQLite3
- **Authentication:** Django Authentication System
- **Image Upload:** Django ImageField
- **Language:** Python 3

---

# 📂 Project Structure

```text
Django-Twitter/
│
├── headq/
│   ├── headq/
│   │   ├── settings.py
│   │   ├── urls.py
│   │   ├── media/
│   │   ├── static/
│   │   └── templates/
│   │       ├── layout.html
│   │       └── registration/
│   │           ├── login.html
│   │           ├── register.html
│   │           └── logged_out.html
│   │
│   ├── tweet/
│   │   ├── migrations/
│   │   ├── templates/
│   │   │   ├── index.html
│   │   │   ├── tweet_form.html
│   │   │   ├── tweet_list.html
│   │   │   └── tweet_confirm_delete.html
│   │   ├── admin.py
│   │   ├── forms.py
│   │   ├── models.py
│   │   ├── urls.py
│   │   └── views.py
│   │
│   ├── manage.py
│   ├── db.sqlite3
│   └── requirements.txt
│
└── README.md
```

---

# 🚀 Installation

## Clone the repository

```bash
git clone https://github.com/<your-username>/Django-Twitter.git
```

```bash
cd Django-Twitter/headq
```

---

## Create Virtual Environment

### Windows

```bash
python -m venv .venv
```

Activate it

```bash
.venv\Scripts\activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Apply Migrations

```bash
python manage.py migrate
```

---

## Run the Server

```bash
python manage.py runserver
```

Open your browser and visit:

```
http://127.0.0.1:8000/
```

---

# 👤 User Functionalities

### Authentication

- Register a new account
- Login
- Logout

### Tweets

- Create Tweet
- Upload Image
- View All Tweets
- Edit Own Tweet
- Delete Own Tweet

---

# 📌 Future Improvements

- ❤️ Like Tweets
- 💬 Comments
- 👥 Follow/Unfollow Users
- 🔍 Search Tweets
- 🏷️ Hashtags
- 📄 User Profiles
- Infinite Scrolling
- Notifications

---

# 📦 Requirements

- Python 3.13+
- Django
- Pillow

---

# 📜 License

This project is developed for educational purposes and personal learning.

---

# 👨‍💻 Author

**Bhavuk Mahajan**

- GitHub: https://github.com/bhavukm007
- LinkedIn: https://www.linkedin.com/in/bhavuk-mahajan/

---

⭐ If you found this project useful, consider giving it a **star** on GitHub.
