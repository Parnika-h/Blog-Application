# College Blog Application

A production-grade Django blog platform built with PostgreSQL and modular Django architecture. The application supports full blog publishing workflows with authentication, comments, tagging, RSS feeds, pagination, search, sitemap generation, and SEO-friendly backend design.

---

## Features

* User Authentication & Authorization
* Blog Post Creation and Management via Django Admin
* Comment System for Posts
* Tagging Support for Content Categorization
* Similar Post Recommendation Logic
* Full-Text Search Functionality
* Email Sharing for Blog Posts
* Pagination for Optimized Navigation
* RSS Feed Generation
* Dynamic XML Sitemap for SEO
* Custom Django Template Tags
* PostgreSQL-backed ORM Models

---

## Tech Stack

* **Backend:** Django, Python
* **Database:** PostgreSQL
* **Frontend:** HTML, CSS
* **Tools:** Git, GitHub

---

## Installation

```bash
git clone <your-repository-url>
cd college_blog
python -m venv venv
venv\Scripts\activate      # Windows
pip install -r requirements.txt
```

---

## Database Setup

```bash
python manage.py migrate
```

(Optional: Load sample data)

```bash
python manage.py loaddata mysite_data.json
```

---

## Run Development Server

```bash
python manage.py runserver
```

Open in browser:

```text
http://127.0.0.1:8000/
```

---

## Project Structure

```text
college_blog/
│
├── blog/                  # Main blog application
├── college_blog/          # Project settings/configuration
├── manage.py
├── requirements.txt
└── mysite_data.json
```

---

## Learning Outcomes

This project strengthened practical understanding of:

* Django ORM and Model Relationships
* Modular Django App Architecture
* Backend Authentication Systems
* Database Query Optimization
* SEO and Syndication Features in Web Apps
* Scalable Full-Stack Application Design

---

## Author

**Parnika Haldar**
GitHub: https://github.com/Parnika-h
LinkedIn: https://www.linkedin.com/in/parnika-h-283ba3351/
