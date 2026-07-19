# Django Portfolio Website

A personal portfolio website built with **Django** that allows visitors to browse projects while administrators can manage project information through the Django Admin interface.

## Features

- Display portfolio projects
- Project detail pages
- Upload project images
- Django Admin panel
- Responsive HTML templates
- SQLite database
- Static and media file handling

## Technologies Used

- Python 3
- Django
- HTML5
- CSS3
- Bootstrap
- SQLite

## Project Structure

```
rp-portfolio/
│
├── pages/
├── projects/
├── personal_portfolio/
├── uploads/
├── static/
├── templates/
├── manage.py
├── requirements.txt
└── README.md
```

## Installation

Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/rp-portfolio.git
```

Move into the project

```bash
cd rp-portfolio
```

Create a virtual environment

```bash
python -m venv venv
```

Activate it

### Windows

```bash
venv\Scripts\activate
```

### Linux/macOS

```bash
source venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run database migrations

```bash
python manage.py migrate
```

Create an administrator account

```bash
python manage.py createsuperuser
```

Start the development server

```bash
python manage.py runserver
```

Open your browser

```
http://127.0.0.1:8000/
```

Admin panel

```
http://127.0.0.1:8000/admin/
```

## Media Uploads

Uploaded project images are stored using Django's media handling.

```
MEDIA_ROOT = uploads/
MEDIA_URL = /media/
```

## Future Improvements

- Project categories
- Search functionality
- Contact form
- User authentication
- PostgreSQL support
- REST API
- Project filtering

## License

This project is for educational and portfolio purposes.