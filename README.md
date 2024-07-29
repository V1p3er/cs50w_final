# Pig Game with Django Backend

## Overview

This project is an online version of the Pig dice game, implemented with JavaScript for the front-end and Django for the back-end. Users can log in, play the game, and track their scores and game history.

## Features

- **Real-Time Gameplay**: Dynamic game state updates.
- **Score Tracking**: Persistent score and game history.
- **Responsive Design**: Optimized for both desktop and mobile.

## Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone git@github.com:V1p3er/cs50w_final.git
   cd cs50w_final

   ```

2. **Set Up the Virtual Environment**:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run Migrations**:
   ```bash
   python manage.py migrate
   ```

5. **Create a Superuser**:
   ```bash
   python manage.py createsuperuser
   ```

6. **Run the Development Server**:
   ```bash
   python manage.py runserver
   ```

7. **Access the Application**:
   Open your web browser and go to `http://127.0.0.1:8000/`.


Enjoy playing the Pig Game! For any questions or feedback, feel free to reach out.
