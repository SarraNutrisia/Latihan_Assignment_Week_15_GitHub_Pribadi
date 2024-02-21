Password Database (Supabase) : C0VMcP9EUD8FajjB

## step installer: (Using Powershell / Git Bash / Command Prompt --> Run as Administrator)
1. pip install poetry (global only once)
2. poetry new flaskzooapi --name app
3. cd flaskzooapi
4. python -m venv .venv
5. powershell Set-ExecutionPolicy Bypass
6. .venv\Scripts\activate
7. poetry config --list
8. poetry config virtualenvs.in-project true (global only once)
9. poetry add Flask
10. Flask --version
11. pip install flask
12. poetry add poetry-dotenv-plugin

## step run:
1. poetry run flask --app app run


## step for manual database setup:
1. poetry add Flask_SQLAlchemy (install flask_sqlalchemy)
2. poetry add psycopg2 (install psycopg2)