# Workout Gym Web Application

This is a **Gym Management System** built with **Flask** (Front-End only), a Python web framework. The web app provides an interactive platform where users can view membership plans, learn about the gym, sign up, log in, and explore the gallery.

## Features

- **Home Page**: Overview of the gym, including a welcome message and key highlights.
- **Membership Plans**: Four membership options with detailed pricing and benefits.
- **About Us**: Information about the gym's mission, facilities, and trainers.
- **Gallery**: A collection of gym images to showcase the environment.
- **Login & Registration**: Pages for users to log in or create an account.
- **Password Recovery**: Option for users to recover forgotten passwords.

## Technologies Used

- **Flask**: Web framework used for building the application.
- **HTML/CSS**: For creating the front-end structure and design.
- **Jinja2**: Templating engine used to generate dynamic content.

## Folder Structure

```
/project_root
  /static
    /images       # Store images like gym photos
    /css          # CSS files for styling
  /templates
    - base.html   # Base template with common layout
    - index.html  # Home page
    - membership.html  # Membership plans page
    - about.html   # About us page
    - gallery.html  # Gallery page
    - login.html   # Login page
    - register.html  # Registration page
    - forget.html   # Password recovery page
  app.py          # Main application file
  requirements.txt  # Project dependencies
```

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/nu2911/workoutApp.git
   cd workout-gym-flask
   ```

2. **Install the dependencies**:
   Create a virtual environment and install the required libraries:
   ```bash
   python3 -m venv venv
   venv\Scripts\activate
   pip install -r requirements.txt
   ```

3. **Run the app**:
   ```bash
   python app.py
   ```
   The app will be accessible at `http://127.0.0.1:5000/`.

## Dependencies

- **Flask**: Web framework for Python
- **Jinja2**: Templating engine (used by Flask)

To install the required dependencies, run:
```bash
pip install -r requirements.txt
```

## License

This project is open source under the MIT License.
