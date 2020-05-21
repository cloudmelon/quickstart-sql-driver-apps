## Run Application

py -3 -m venv env
env\scripts\activate
pip install -r requirements.txt
SET FLASK_APP=app.py
flask run