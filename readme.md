[Devlopment Env]
conda env list                                  # List all conda envs
conda activate django                           # Activate conda env
pip install virtualenv                          # Install venv packege
virtualenv venv                                 # Create venv
source venv/bin/activate                        # Activate venv
deactivate                                      # Deactivate venv


[Application Requrments]                        # Installed packeges
pip install Django
pip install Pillow
pip freeze > ../requirements.txt                # Create file with all requrments

[Django commands]
django-admin startproject real_estate           # Craete new django project
python manage.py migrate                        # Migrate modules in database
python manage.py runserver                      # Run Django server
python manage.py createsuperuser                # Create SuperUser
python manage.py startapp listings              # Add app to existing project
python manage.py makemigrations                 # Create migration files for project
python manage.py migrate                        # Migrate modules in database


