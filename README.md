# Django-GraphQL-React-Demo

Introduce how to use GraphQL to connect Django and React

## Audience
The project is intended for engineers who want to know how to use GraphQL to connect Django and React. There is a basic GraphQL server in backend directory and GraphQL client in frontend directory. If you want to know the details, you can read the following Medium articles.

## Backend
- Directory: backend
- Language: Python3
- Framework: Django

### Set Up
- `cd backend`
- `virtualenv venv`
- `source venv/bin/activate`
- `pip install -r requirements.txt`
- `cd myproject`
- `python manage.py migrate`
- `python manage.py runserver`
- Visit [http://localhost:8000/graphql](http://localhost:8000/graphql)

## Frontend
- Directory: frontend
- Library: React

### Set Up
- `cd frontend/app`
- `npm install`
- `npm start`
- Visit [http://localhost:3000](http://localhost:3000)
