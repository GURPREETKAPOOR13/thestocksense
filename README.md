# thestocksense

cd webapp

pipenv shell
python -m venv myvenv  
myvenv\Scripts\activate
pip install -r reqirements.txt
python manage.py migrate
python manage.py runserver
