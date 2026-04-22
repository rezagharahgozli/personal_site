# Personal Portfolio Website

A personal portfolio website built with **Django, HTML, CSS, and Bootstrap** to showcase my skills, projects, and professional experience as a software engineer.

The website includes sections such as profile introduction, technical skills, projects, work experience, education, and contact information.

---

## Features

- Personal profile section
- Skills with technology badges
- Projects showcase
- Work experience
- Education section
- Contact information
- Downloadable resume
- Responsive design using Bootstrap

---

## Technologies Used

### Backend
- Python
- Django

### Frontend
- HTML5
- CSS3
- Bootstrap

### Database
- SQLite (default Django database)

### Tools
- Git
- GitHub
- Render (for deployment)

---

## Project Structure


personal_site
│
├── base
│
├── static
│ ├── css
│ ├── images
│ └── files
│
├── templates
│
├── manage.py
│
└── personal_site
├── settings.py
├── urls.py
└── wsgi.py


---

## Installation

Clone the repository


git clone https://github.com/rezagharahgozli/portfolio.git


Go to project folder


cd portfolio


Install dependencies


pip install -r requirements.txt


Run migrations


python manage.py migrate


Run the development server


python manage.py runserver


Open in browser


http://127.0.0.1:8000


---

## Deployment

The project can be deployed using **Render**.

Build Command


pip install -r requirements.txt && python manage.py collectstatic --noinput


Start Command


gunicorn personal_site.wsgi:application


---

## Author

Mohammadreza Gharahgozlee

Software Engineer

GitHub:  
https://github.com/rezagharahgozli

Location:  
Quebec, Canada

---

## License

This project is open-source and available for educational and personal use.
