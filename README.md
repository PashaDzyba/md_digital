MD DIGITAL API

API for adding teams and persons

Description:

This API allows for the management of "teams" and the "people" within those teams. It provides endpoints for creating, retrieving, updating, and deleting teams, as well as adding people to teams.

Dependencies:

* Python 3.8+
* Django 3.2+
* Django REST Framework
* PostgreSQL
* `drf-yasg` for Swagger documentation

Install the required packages:

pip install -r requirements.txt

Setting Up a Development Environment:

* Create a PostgreSQL database for the project
* Configure the DATABASES setting in settings.py to connect to your PostgreSQL database
* Apply the migrations: python manage.py migrate


Running the Application:

* Start the development server:python manage.py runserver
* Access the API root at 'http://127.0.0.1:8000/api/'

API Reference:

Endpoints:

Teams:
* GET /api/teams/ - List all teams
* POST /api/teams/ - Create a new team
* GET /api/teams/{teamId}/ - Retrieve a specific team
* PUT /api/teams/{teamId}/ - Update a specific team
* DELETE /api/teams/{teamId}/ - Delete a specific team

People
* GET /api/people/ - List all people
* POST /api/people/ - Create a new person
* GET /api/people/{personId}/ - Retrieve a specific person
* PUT /api/people/{personId}/ - Update a specific person
* DELETE /api/people/{personId}/ - Delete a specific person

Swagger Documentation:
* Access the Swagger UI at http://127.0.0.1:8000/swagger/
* Access the ReDoc UI at http://127.0.0.1:8000/redoc/



