# 🌐 BlogSphere

> Where ideas connect and stories grow.

A modern Flask blogging platform with user authentication, blog posts, comments, and image uploads.

## ✨ Features

- **User Authentication**: Register, Login, Logout with password hashing
- **Blog Posts**: Create, Edit, Delete your own posts
- **Image Uploads**: Upload images for blog posts and profile pictures
- **Comment System**: Users can comment on posts
- **Modern UI**: Dark theme inspired by Medium/Dev.to
- **Responsive Design**: Works on all devices
- **Secure**: Password hashing, CSRF protection, file upload validation

## 🛠️ Tech Stack

- **Backend**: Python Flask
- **Database**: SQLite (Flask-SQLAlchemy)
- **Authentication**: Flask-Login
- **Frontend**: HTML, CSS, Jinja2 Templates
- **Image Handling**: Werkzeug secure_filename

## 📦 Installation

### Prerequisites

- Python 3.8 or higher
- pip (Python package manager)

📁 Project Structure

Copy code
BlogSphere/
│
├── app.py                 # Main Flask application
├── create_db.py           # Database initialization script
├── requirements.txt       # Python dependencies
├── README.md             # This file
│
├── instance/
│   └── blogsphere.db     # SQLite database (auto-generated)
│
├── static/
│   ├── css/
│   │   └── style.css     # Main stylesheet
│   └── uploads/
│       └── profile_pics/ # User profile pictures
│
└── templates/
    ├── base.html
    ├── index.html
    ├── posts.html
    ├── auth/
    │   ├── login.html
    │   └── register.html
    └── posts/
        ├── create_post.html
        ├── edit_post.html
        ├── post_detail.html
        └── posts.html
