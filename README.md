Creating a Movie Rater API

mkdir 'movieraterapi' && cd 'movieraterapi'
python -m venv venv
venv\Scripts\activate.bat
prompt (venv) $g
touch requirements.txt
echo 'Django == "3.0.*" > requirements.txt
echo 'Djangorestframework == "3.11.*" > requirements.txt
touch README.md

set up git repo

touch .gitignore
echo 'venv/' > .gitignore

django-admin startproject movierater .
django-admin startapp api


edit Django
