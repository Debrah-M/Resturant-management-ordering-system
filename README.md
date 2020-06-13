# Resturant-management-ordering-system

## Installation

1. Clone the repo and get into the directory

    ```code
    git clone https://github.com/Debrah-M/Resturant-management-ordering-system.git
    cd Resturant-management-ordering-system
    ```

2. Launch a Dedicated Virtual Environment  (Virtual Environment should run on Python3.8+).

    ```code
    virtualenv -p /path/to/python/3 venv
    source venv/bin/activate
    ```

3. Install Package Requirements.

    ```code
    pip install -r requirements.txt
    ```

2. get into the rmos directory and Migrate the database.

    ```code
    cd rmos
    python manage.py makemigrations
    python manage.py migrate
    ```

4. OPTIONAL: Run the Server to see if it's working

    ```code
    python manage.py runserver
    ```
