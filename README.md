# CapWeb

This project is a Django backend web application.

## Setup Instructions

### 1. Clone the Repository
Clone this repository to your local machine:
```sh
git clone https://github.com/chadixearth/CapWeb.git
cd CapWeb
```

### 2. Create and Activate a Virtual Environment
It is recommended to use a Python virtual environment:
```sh
python -m venv venv
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
```

### 3. Install Dependencies
Install Django and any other required packages:
```sh
pip install django
```

If you have additional dependencies, add them to a `requirements.txt` file and run:
```sh
pip install -r requirements.txt
```

### 4. Apply Migrations
Navigate to the backend directory and apply migrations:
```sh
cd backend
python manage.py migrate
```

### 5. Run the Development Server
Start the Django development server:
```sh
python manage.py runserver
```

The server will start at [http://127.0.0.1:8000/](http://127.0.0.1:8000/).

---

## Project Structure
- `backend/` - Django project and app code
- `venv/` - Python virtual environment (not tracked in git)

---

## Notes
- Make sure you are using Python 3.8 or higher.
- If you add new dependencies, update your `requirements.txt` with `pip freeze > requirements.txt`. 