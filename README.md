Crop Planting Assistant

A web-based crop planting assistant designed to help users organize and manage their planting activities, track crop schedules, and maintain useful farming records.

Features

- User Authentication: Register, log in, and manage individual sessions.
- Planting Calendar: Generate crop planting calendars based on planting dates.
- Activity Tracking: View, add, complete, undo, and delete planting activities.
- Reminders: Keep track of upcoming planting activities and tasks.
- Crop Information: Browse available crop information.
- Farm Notes: Create, view, and delete personal planting notes.
- Calendar Management: Select and manage planting calendars.

Technologies Used

- Python
- Flask
- SQLite
- HTML5
- CSS3
- Gunicorn

Installation and Setup

Prerequisites

- Python 3.10 or later
- pip

1. Clone the Repository

git clone https://github.com/IBdaEdgerunnner/crop-planting-assistant.git
cd crop-planting-assistant

2. Create a Virtual Environment

python -m venv venv

Activate it:

Windows

venv\Scripts\activate

Linux/macOS

source venv/bin/activate

3. Install Dependencies

pip install -r requirements.txt

4. Run the Application

python app.py

Open your browser and visit:

http://127.0.0.1:5000

Deployment

The application is deployed using Render.

Live Application: https://crop-planting-assistant.onrender.com

Production deployment requires the following environment variables:

Variable| Description
"PRODUCTION"| Set to "1" to enable production settings
"SECRET_KEY"| Secure secret key used for session signing

Database

The application uses SQLite to store user accounts, planting activities, and notes.

Project Structure

crop-planting-assistant/
├── app.py
├── requirements.txt
├── crop_assistant.db
├── templates/
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   └── ...
└── static/
    └── style.css

License

This project is developed for educational purposes.
