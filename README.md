# EduFind - Personal Learning Assistant

EduFind is a Personal Learning Assistant (PLA) web application built with Django. It helps users discover educational resources, manage their learning progress, and collaborate with others.

## Features

- User authentication: Users can create accounts and log in securely.
- Resource discovery: Users can search for educational resources based on their interests and needs.
- Progress tracking: Users can track their learning progress and set goals.
- Collaboration: Users can collaborate with others through discussion forums and group activities.
- Mobile compatibility: The interface is responsive and optimized for mobile devices.

## Installation

To run EduFind locally, follow these steps:

1. Clone the repository:
   git clone https://github.com/your-username/EduFind.git
2.Install dependencies:

  pip install -r requirements.txt

3.Set up the database:

python manage.py migrate

4.Create a superuser:


python manage.py createsuperuser

Run the development server:


    python manage.py runserver

    Access the application at http://localhost:8000/

Usage

    Register an account or log in if you already have one.
    Explore educational resources using the search feature.
    Track your learning progress and collaborate with others.
    Enjoy learning with EduFind!

Contributing

Contributions are welcome! If you'd like to contribute to EduFind, please follow these steps:

    Fork the repository.
    Create a new branch (git checkout -b feature-name).
    Make your changes.
    Commit your changes (git commit -am 'Add new feature').
    Push to the branch (git push origin feature-name).
    Create a new pull request.
