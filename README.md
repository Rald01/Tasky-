markdown
Copy code
# Tasky

Tasky is a task management application built with Django,  TailwindCSS and Jquery for frontend.

## Features
- User authentication and authorization
- Task creation, editing, and deletion
- Task status update via drag-and-drop
- Filtering and sorting tasks
- Dynamic user assignment

## Setup

1. **Clone the repository**:
    ```sh
    git clone https://github.com/Rald01/Tasky-.git
    cd Tasky-
    ```

2. ** activate virtual environment**:
    ```sh
    source env/bin/activate
    ```

3. **Install dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

4. **Apply migrations**:
    ```sh
    python manage.py migrate
    ```

5. **Create a superuser**:
    ```sh
    python manage.py createsuperuser
    ```

6. **Run the development server**:
    ```sh
    python manage.py runserver 
    ```

7. **Access the application**:
    Open your web browser and go to `http://127.0.0.1:8000/`.

## Testing

Run the tests using:
```sh
python manage.py test