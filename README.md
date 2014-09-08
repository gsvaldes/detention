cd projects
see http://www.django-rest-framework.org/tutorial/1-serialization
sudo apt-get install virtualenv
virtualenv detention
source detention/bin/activate 
pip install django
pip install djangorestframework
pip install pygments  # needed for rest framework tutorial, not actual project
sudo apt-get install postgresql  libpq-dev
sudo apt-get install python-dev #needed to install psycopg2
pip install psycopg2
pip install djangorestframework-gis
cd ~
django-admin.py startproject texas_detention
cd texas_detention
python manage.py startapp detention
