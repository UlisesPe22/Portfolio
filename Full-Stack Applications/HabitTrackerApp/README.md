# HabitApp
This app is designed to help you track and manage your habits. Below are the instructions to get your app up and running on your local machine.

## Getting Started

Follow these steps to set up and run the app on your computer.

### Prerequisites

- Python 
- Visual Studio Code
- flask

### Installation

1. Download the necessary files.
2. Go to downloads and extract all from the zip file "HabitApp-main.zip".
3. Open the "HabitApp-main" on Visual Studio. **Note: make sure to be in the correct folder. If you are not in the correct folder, the next step is not going to work**
5. Open a new terminal on Visual Studio and write "pip install -r requirements.txt" then press enter.If there is an "Error", don't worry, it should be fine (if you find problems check the note at the end of the document)
6. Finally start the database. open a new terminal and type "python". Once you are in the python interpreter type and press enter after each command.
- "from app import app, db"
- "db.create_all()"
- "exit()"
6. Open a new terminal and type "python -m flask run". Click on the link and try the app.

  **Note: if you have issues with the requierments.txt file, you can alternativly use this command:**"pip install Flask Flask-SQLAlchemy Flask-Login Flask-WTF Flask-Bcrypt APScheduler email_validator"


  

