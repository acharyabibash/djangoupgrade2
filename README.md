# djangoupgrade

## OR django-exp/mysite on local computer

## this project is a test to upgrade djangoproject with django version 2.2 to 3.2


clone the repository__



create the virtual environment with name hawa__



activate virtual environment with hawa/Scripts/Activate__

install an old version of django like 2.2 LTS(at least otherwise the project may not work)__

install django-upgrade package with command : pip install django-upgrade__
cd into polls/models.py file and run: django-upgrade --target-verion 3.2 models.py__4
this will upgrade poll/models.py file like changing NullBooleanField () to BooleanField() so that the code of polls.models.py is from django 2.2 to django 3.2 version__
upgrade version of django also by : pip install --upgrade django==3.2 (3.2 is an example)__
this uninstall old version of django like 2.2 installed in hawa virtualenv and install 3.2 django version__

cd into mysite__
python manage.py runserver to run project__


## generate requirements.txt
use pip freeze > requirements.txt to generate requirements.txt file with all the packages installed<br/>

if u just want to run this project and dont want to upgrade the project experimenting<br/>

just clone the project<br/>

run pip install -r requirements.txt<br/>
