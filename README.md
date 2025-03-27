# Flask API with MySQL Database

## Setup Instructions

1. Clone the repository
2. Install the required dependencies
    ```bash
    pip install -r requirements.txt
    ```
3. Set up the MySQL database (see `app.py` for connection details)
4. Run the Flask app
    ```bash
    python app.py
    ```
    
## Endpoints

### /students
- Returns a list of 10 students with their names and enrolled programs.

### /subjects
- Returns a list of subjects associated with the Software Engineering program, grouped by academic year.

## Dependencies
- Flask
- Flask-SQLAlchemy
- MySQL

