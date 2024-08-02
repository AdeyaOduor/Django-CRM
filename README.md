mkdir djandoCrm
cd djandoCrm
python3 -m venv crmenv
source myenv/bin/activate 
pip install django
pip install mysql-connector
pip install mysql-connector-python3
django-admin startproject djangoCrm

//install mysql on local machine from official website {dev.mysql.com}
cd djangoCrm
python3 manage.py startapp website
code .

 python manage.py makemigrations
 python manage.py migrate
 python manage.py createsuperuser, and enter user and p/word
 python manage.py runserver
       # OR
 python3 ./djangoCrm/manage.py makemigrations
 python3 ./djangoCrm/manage.py migrate
 python3 ./djangoCrm/manage.py createsuperuser, and enter user and p/word
 python3 ./djangoCrm/manage.py runserver
