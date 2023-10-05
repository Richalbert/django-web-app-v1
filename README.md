# django-web-app
D'apres le tuto de Openclassroom

# Creation de l'environnement virtuel
mkdir django-web-app && cd django-web-app  
python3 -m venv .env  
source .env/bin/activate  

# Install du module Django
pip install --upgrade pip  
pip install django  
pip freeze > requirements.txt  

# Creation du projet
django-admin startproject merchex  

# Creation de l'application listings  
python manage.py startapp listings  

#EOF
