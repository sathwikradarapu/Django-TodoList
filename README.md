# 📝 Django TodoList

A simple yet powerful **Task Management System** built using the **Django MVT architecture**.  
This project allows users to **Create**, **Read**, **Update**, and **Delete (CRUD)** tasks with database persistence and role-based admin management.

---

## 🛠️ Tech Stack

- **Python 3.x**
- **Django 3.x or higher**
- **SQLite** (default lightweight database)
- **HTML5, CSS3** (Jinja2 Templates)
- **Bootstrap** (for responsive UI)

---

## ✨ Features

- ➕ **Add New Tasks** using Django forms
- 📝 **Edit Existing Tasks** with validation
- ✅ **Delete Completed Tasks** with one click
- 📋 **View All Tasks** in a neatly organized list
- 🔐 **CSRF Protection** enabled on all forms
- 🛡️ **Role-Based Admin Panel Access** for managing tasks
- 🎨 **User-friendly and Responsive UI** built with Jinja2 templating and Bootstrap
- 🔄 **Database Persistence** using SQLite
- 📈 **Efficient Task Management** through Django’s powerful backend

---


---

## 🚀 How to Run Locally

### Requirements:
- Python 3.x installed
- Django 3.x or higher installed

---

### Steps to Run:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/sathwikradarapu/Django-TodoList.git
    cd Django-TodoList
    ```

2. **Create a virtual environment:**

    ```bash
    python3 -m venv venv
    ```

3. **Activate the virtual environment:**

    - For Windows:

      ```bash
      venv\Scripts\activate
      ```

    - For macOS/Linux:

      ```bash
      source venv/bin/activate
      ```

4. **Install the dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

5. **Apply migrations:**

    ```bash
    python manage.py migrate
    ```

6. **Create a superuser (for Admin Panel access):**

    ```bash
    python manage.py createsuperuser
    ```

7. **Run the development server:**

    ```bash
    python manage.py runserver
    ```

8. Open your browser and visit:  
   [http://127.0.0.1:8000/](http://127.0.0.1:8000/)  (User Interface)  
   [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/) (Admin Panel)

---

## 💡 Key Learning Outcomes

- Hands-on experience with the **Django MVT** (Model-View-Template) architecture
- Building dynamic web applications using **Jinja2 templates**
- Creating **Django Forms** with **CSRF protection**
- Implementing **CRUD operations** with database persistence
- Configuring and using the **Django Admin Panel** for role-based access control
- Building **responsive UIs** using Bootstrap 4.5

---

## 🧑‍💻 Contribution Guidelines

Contributions are welcome!  
You can **fork** this repository, **enhance the project** (like adding deadlines, priorities for tasks, or user authentication), and **submit a pull request** 🚀.

---

## 🎯 Future Scope

- Add task priority and deadlines
- Email notification reminders
- Search and filter tasks
- REST API integration using Django REST Framework (DRF)

---

Developed with ❤️ by **Sathwik Radarapu**


