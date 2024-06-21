# google-form-


## Features

- User Registration
- User Login
- Google OAuth 2.0 Authentication
- User Dashboard
- SQLite Database

## Getting Started

### Prerequisites

- Python 3.x
- Virtualenv
- Git

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   cd <your-repo-name>
   

Replace YOUR_GOOGLE_CLIENT_ID and YOUR_GOOGLE_CLIENT_SECRET with your actual credentials in the app.py file.

python
Copy code
google = oauth.remote_app(
    'google',
    consumer_key='YOUR_GOOGLE_CLIENT_ID',
    consumer_secret='YOUR_GOOGLE_CLIENT_SECRET',
    ...
)
Running the Application
Create the Database

bash
Copy code
python app.py
This will create users.db SQLite database.

Run the Flask Application

bash
Copy code
flask run
Access the Application

Open your web browser and go to http://localhost:5000/.

Directory Structure
Copy code
jewellery_auth_app/
│
├── app.py
├── requirements.txt
├── templates/
│   ├── index.html
│   ├── login.html
│   ├── signup.html
│
└── venv/
