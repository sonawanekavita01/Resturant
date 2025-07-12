# 🍽️ SmartDine - Django Restaurant Reservation System

SmartDine is a Django-based web application designed for restaurant owners to streamline the table reservation process. It allows customers to book tables online by submitting a simple form. Upon booking, a confirmation email is sent to the restaurant's registered email, ensuring efficient reservation management.
The system also integrates Google Maps to help users locate the restaurant easily. Admins can view and manage all bookings from the Django admin dashboard.
Whether you're a developer looking to understand Django's form handling and email systems, or a restaurant owner in need of a digital solution — this project provides a practical, real-world example of modern web development using Django.


---

## 🚀 Features

- ✅ Table reservation form
- ✅ Email confirmation to admin/restaurant
- ✅ Google Maps integration
- ✅ Responsive front-end UI
- ✅ Admin panel to view/manage bookings

---

## 🛠️ Tech Stack

- **Backend**: Python, Django
- **Frontend**: HTML5, CSS3, Bootstrap
- **Database**: SQLite (default, easy to swap)
- **Email Service**: Gmail SMTP
- **Maps**: Google Maps API

---

## 📦 Project Structure

Resturant_Project/
├── Base_App/
│ ├── templates/
│ ├── static/
│ ├── views.py
│ ├── models.py
│ └── urls.py
├── Resturant_Project/
│ ├── settings.py
│ ├── urls.py
│ └── wsgi.py
├── db.sqlite3
├── manage.py
└── README.md



## 🧰 Prerequisites

- Python 3.9+
- pip
- virtualenv (recommended)
- Google account (for SMTP and Maps API key)



## 🛠️ Installation Steps
---
# Clone the repo
git clone https://github.com/your-username/restaurant-app.git
cd restaurant-app

# Create and activate virtual environment
python -m venv venv
source venv/bin/activate     # On Windows use: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
---
# Create environment variables (Or use a .env file if preferred)
set EMAIL_HOST_USER=your_email@gmail.com
set EMAIL_HOST_PASSWORD=your_app_password
set GOOGLE_MAPS_API_KEY=your_google_maps_api_key
---
# Run migrations and start server
python manage.py migrate
python manage.py runserver

---



📬 Contact
Name: Kavita Sonawane
📧 Email: sonawanekavita011@gmail.com




