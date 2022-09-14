# djangoupgrade

## OR django-exp/mysite on local computer

## this project is a test to upgrade djangoproject with django version 2.2 to 3.2


clone the repository



create the virtual environment with name hawa



activate virtual environment with hawa/Scripts/Activate

install an old version of django like 2.2 LTS(at least otherwise the project may not work)

install django-upgrade package with command : pip install django-upgrade
cd into polls/models.py file and run: django-upgrade --target-verion 3.2 models.py
upgrade version of django also by : pip install --upgrade django==3.2 (3.2 is an example)
this uninstall old version of django like 2.2 installed in hawa virtualenv and install 3.2 django versio
generate a 

cd into mysite
python manage.py runserver to run project


## generate requirements.txt
use pip freeze > requirements.txt to generate requirements.txt file with all the packages installed

if u just want to run this project and dont want to upgrade the project experimenting

just clone the project

run pip install -r requirements.txt