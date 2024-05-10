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
   ```bash
   git clone https://github.com/your-username/EduFind.git
   ```

2. Navigate to the project directory:
   ```bash
   cd EduFind
   ```

3. Create and activate a virtual environment (optional but recommended):
   ```bash
   python -m venv env
   source env/bin/activate  # For Linux/macOS
   .\env\Scripts\activate    # For Windows
   ```

4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

5. Set up the database:
   ```bash
   python manage.py migrate
   ```

6. Create a superuser:
   ```bash
   python manage.py createsuperuser
   ```

7. Run the development server:
   ```bash
   python manage.py runserver
   ```

8. Access the application at [http://localhost:8000/](http://localhost:8000/)

## Usage

1. Register an account or log in if you already have one.
2. Explore educational resources using the search feature.
3. Track your learning progress and collaborate with others.
4. Enjoy learning with EduFind!

## Contributing

Contributions are welcome! If you'd like to contribute to EduFind, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature-name`).
6. Create a new pull request.


