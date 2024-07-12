# calculator
# Professional Web Calculator

A sleek, responsive calculator web application built with HTML, SCSS, and JavaScript, featuring a Python backend.

## Features

- Responsive design for all devices
- Dynamic, animated background
- Basic arithmetic operations (addition, subtraction, multiplication, division)
- Advanced functions: percentage calculation and positive/negative toggle
- Clear function
- Elegant UI with a frosted glass effect
  ![1](https://github.com/user-attachments/assets/68cab31f-6a5c-432d-8a15-110fd7fb4b53)


## Technologies Used

- HTML5
- SCSS/CSS3
- JavaScript
- Python (Django framework)

## Installation

1. Clone the repository:
2. git clone https://github.com/yourusername/Professional-Web-Calculator.git
Copy
2. Navigate to the project directory:
cd Professional-Web-Calculator
Copy
3. Install the required dependencies:
pip install -r requirements.txt
Copy
4. Run migrations:
python manage.py migrate
Copy
5. Start the development server:
python manage.py runserver
Copy
6. Open your browser and navigate to `http://localhost:8000`

## Usage

[Provide instructions on how to use the calculator]

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgements



## Contact

Your Name -Mumtaz Ali - 
Your Email- engrmumtazali01@gmail.com

Project Link: (https://github.com/engrmumtazali0112/calculator)

Create a .gitignore file in the root of your project. Here's a basic one for a Python/Django project:


*.pyc
__pycache__/
*.py[cod]
*$py.class

# Django
*.log
local_settings.py
db.sqlite3
db.sqlite3-journal

# Static files
/static/

# Media files
/media/

# Virtual environment
venv/
env/

# IDE specific files
.vscode/
.idea/

# OS generated files
.DS_Store
.DS_Store?
._*
.Spotlight-V100
.Trashes
ehthumbs.db
Thumbs.db

Create a requirements.txt file in the root of your project with your Python dependencies:

Django==3.2.4
django-sass-processor==1.1
libsass==0.21.0
