# ThewayShop - E-Commerce Landing Page

![Project Demo](demo.webp)

## Overview

**ThewayShop** is a fully responsive e-commerce web application built with **Django**. It provides an engaging, professional storefront with elegant layouts, high-quality product displays, and essential e-commerce features.

Key features include:
- **Clean Homepage**: A visually appealing hero slider and featured categories.
- **Product Spotlights**: Structured and responsive grid layouts for highlighting specific kinds of apparel.
- **Social Connectivity**: Integration with Instagram feeds and dedicated blogs.
- **Django Admin (Jazzmin)**: An elegant, modernized admin dashboard using `django-jazzmin`.
- **Custom User Model**: Built-in support for a highly flexible user authentication system (`userauths.User`).

---

## Technical Stack
- **Backend**: Python 3, Django 4.x / 5.x
- **Database**: SQLite3 (default, but can be switched to PostgreSQL/MySQL)
- **Frontend**: HTML5, CSS3, JavaScript
- **Admin Theme**: Django-Jazzmin

---

## 🛠 Installation & Setup

Follow these simple steps to get the environment running on your local machine.

### 1. Requirements

Make sure you have `Python 3.x` installed on your machine.
Clone or download this repository and navigate to its root folder:

```bash
cd e-commerce-site-main
```

### 2. Create a Virtual Environment

It is highly recommended to isolate your project dependencies:
```bash
python -m venv venv
```

Activate the environment:
- **Windows**: `.\venv\Scripts\activate`
- **macOS/Linux**: `source venv/bin/activate`

### 3. Install Dependencies

Install all required packages via `pip`:
```bash
pip install -r requirements.txt
```
> **Note**: This will install Django, Pillow (for image processing), and Django-Jazzmin (for the admin interface).

### 4. Database Setup & Migrations

If you are setting this up for the first time, run the following commands to create the database schema:

```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. Create a Superuser

To access the Django Admin panel, you must create a superuser account:
```bash
python manage.py createsuperuser
```
Follow the prompts to enter your username, email, and password.

### 6. Run the Development Server

Start the local Django server:
```bash
python manage.py runserver
```

Open your browser and navigate to:
- **Homepage**: `http://127.0.0.1:8000/`
- **Admin Panel**: `http://127.0.0.1:8000/admin/`

---

## 📸 Screenshots & Visuals

As shown at the top, the homepage implements a modern UI design. Users can view various items separated into distinct categorical sections:
* **T-Shirts, Wallets, Shoes** widgets
* Blog integration
* Responsive UI scaling down correctly to mobile view

Enjoy shopping with ThewayShop!
