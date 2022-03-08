# Udacity-FSND-Cafe-Drink-System
a simple version of menu item mangagement system.

Coffee Shop Web App is a simple version of menu item mangagement system that allow RBAC(role-based access control) implemented by Auth0. The application features:

1. Menu items Display for customers via Angular and ionic framework.
2. various authentications including password-based and *Single Sign-On (SSO)* Authentication
3. logged-in users have Role-based access control for CRUD API.
4. created RESTful API with PostgreSQL and flask

## Preview:

1. Homepage(item display)
2. login(redirect to Auth0)
3. logged-in interface(active jwt from Auth0)
4. item management interface(barista: access to change, no access to create and delete)
5. item management interface(manage: access to change, create and delete)



## Dependencies:

backend:

- **Virtual Enviornment**
- **PostgreSQL** as our database of choice
- **Python3.7** as our server language and [Flask](http://flask.pocoo.org/)
- [SQLAlchemy](https://www.sqlalchemy.org/) and [Flask-SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com/en/2.x/)
- [Flask-CORS](https://flask-cors.readthedocs.io/en/latest/#)
- [jose](https://python-jose.readthedocs.io/en/latest/)

frontend:

1. **Node and NPM**
2. **Ionic Cli**
3. **Installing project dependencies**
