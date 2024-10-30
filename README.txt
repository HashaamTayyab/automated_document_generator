1-> To run the project first create a local environment running this command in command prompt.
    -> python -m venv env
2-> Activate the local environment in your command prompt:
    -> env/scripts/activate
3-> Download the required frameworks for the project using:
    -> pip install -r requirements.txt
4-> Creating default database migrations for the project.
    -> python manage.py makemigrations
5-> Applying the migrations to the databse:
    -> python manage.py migrate
6-> Running the project in your local server:
    -> python manage.py runserver
