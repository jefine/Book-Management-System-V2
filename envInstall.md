using flask lastest(2.*)

change the manger.py
from flask_script import Manager, Shell


>No module named 'flask._compat'

from flask_script._compat  import text_type

>No module named 'flask_wtf'
pip install flask_wtf



start the python server

python manage.py runserver