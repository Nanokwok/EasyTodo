# EasyTodo

EasyTodo is a simple and user-friendly Todo application built with Django. It allows users to manage their tasks efficiently with features like authentication, CRUD operations, and optional image uploads.

## Features
- User authentication (Login/Signup)
- Add, update, and delete tasks
- Change task status (Pending, In Progress, Done)
- Optional image upload with tasks
- SQLite/PostgreSQL database support

## Tech Stack
- **Backend:** Django (Python)
- **Frontend:** Django Templates + Tailwind CSS
- **Database:** PostgreSQL
- **Authentication:** Django's built-in auth system

## Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/EasyTodo.git
   cd EasyTodo
   ```

2. Create and activate a virtual environment:
   - macOS/Linux:
     ```sh
     python -m venv venv
     source venv/bin/activate
     ```
   - Windows:
     ```sh
     python -m venv venv
     venv\Scripts\activate
     ```

3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

4. Configure database (optional: edit `settings.py` for PostgreSQL)

5. Run migrations:
   ```sh
   python manage.py migrate
   ```

6. Start the server:
   ```sh
   python manage.py runserver
   ```

7. Open in browser: [http://127.0.0.1:8000](http://127.0.0.1:8000)

## License
MIT License
