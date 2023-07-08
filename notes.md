conda create -p venv python=3.7 -y
conda activate path

conda install -c anaconda django
django-admin startproject myportfolio

python manage.py runserver

python manage.py startapp base