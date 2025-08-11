# Real Estate Web Application

A full-stack web application for managing real estate properties with user authentication, property management, and admin functionality.

## 🚀 Features

- **User Authentication**: Registration, login, and role-based access (Admin/User)
- **Property Management**: Add, view, update, and delete properties
- **Property Filtering**: Search properties by location, area, and price
- **Admin Panel**: Administrative dashboard for property and user management
- **User Dashboard**: Personal property management for registered users
- **Responsive Design**: Modern UI with Bootstrap and custom CSS

## 🛠️ Tech Stack

### Backend
- **Flask** - Python web framework
- **Flask-SQLAlchemy** - ORM for database operations
- **Flask-MySQLdb** - MySQL database integration
- **MySQL** - Database management system

### Frontend
- **HTML5** - Markup language
- **CSS3** - Styling with custom CSS
- **JavaScript** - Client-side functionality
- **Bootstrap 5** - CSS framework
- **jQuery** - JavaScript library
- **Slick Carousel** - Image carousel component

### Development Tools
- **Poetry** - Python dependency management
- **Gunicorn** - WSGI HTTP server

## 📋 Prerequisites

- Python 3.10+
- MySQL Server
- Poetry (recommended) or pip

## ⚙️ Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd RealEstateWebApp/realestateapp
   ```

2. **Install dependencies**
   ```bash
   # Using Poetry (recommended)
   poetry install
   
   # Or using pip
   pip install -r requirements.txt
   ```

3. **Database Setup**
   - Create a MySQL database named `realestateapp`
   - Update database credentials in `app.py` if needed
   - Run the application to auto-create tables

4. **Run the application**
   ```bash
   python app.py
   ```

5. **Access the application**
   - Open your browser and navigate to `http://localhost:5000`

## 📁 Project Structure

```
realestateapp/
├── app.py              # Main Flask application
├── db.py               # Database models and configuration
├── propertyfetch.py    # Property data handling utilities
├── templates/          # HTML templates
├── static/             # CSS, JS, and image files
├── requirements.txt    # Python dependencies
└── pyproject.toml     # Poetry configuration
```

## 🔑 Key Functionality

- **Public View**: Browse all properties without authentication
- **User Registration**: Create new user accounts
- **User Dashboard**: Manage personal property listings
- **Admin Panel**: Full administrative control over users and properties
- **Property CRUD**: Complete Create, Read, Update, Delete operations
- **Search & Filter**: Find properties based on various criteria

## 🔧 Configuration

Update the following in `app.py` for your environment:
- Database connection settings
- Secret key for sessions
- MySQL host, user, and password

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
