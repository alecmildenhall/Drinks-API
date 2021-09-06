# Drinks-API
Basic Python REST API made with Flask and SQLAlchemy that helps users keep track of their favorite drinks.

Allows users to get a list of all drinks, get a drink's specific description, add a description of a drink, and delete a description of a drink.

**Set Up**
1. Create a new folder for virtual directory to house Drinks API
  - $python3 -m venv .venv
2. Activate
  - $source .venv/bin/activate
3. Install dependencies
  - $pip3 install flask
  - $pip3 install flask-sqlalchemy
4. Create environment variables
  - $export FLASK_APP=application.py
  - $export FLASK_ENV=development
5. Run application
  - $flask run
