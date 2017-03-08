virtualenv ENV  <br />
cd ENV  <br />
source bin/activate<br />
<br />
git init  <br />
git add README.md <br />
git commit -m "first commit"  <br />
git remote add origin https://github.com/MrFoldAnyTen/Django-Web-Page.git <br />
git push -u origin master <br />
<br />
<br />

cd ENV/<br />
source bin/activate<br />
pip install django<br />
python -m django --version<br />
django-admin startproject mysite<br />
<br />
<br />

python manage.py runserver<br />
cd mysite<br />
python manage.py startapp polls<br />
<br />
<br />
set timezone <br />
python manage.py migrate<br />
add installed app <br />
python manage.py makemigrations polls
<br />
(ENV) dylan@Malvin ~/temp/temp/temp/Django-Web-Page/ENV/mysite $ python manage.py makemigrations polls<br />
Migrations for 'polls':<br />
  polls/migrations/0001_initial.py:<br />
    - Create model Choice<br />
    - Create model Question<br />
    - Add field question to choice<br />
(ENV) dylan@Malvin ~/temp/temp/temp/Django-Web-Page/ENV/mysite $ <br />
<br />
python manage.py migrate
<br />
