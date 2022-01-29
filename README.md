# django-tutorial
Django notes:

do not commit vitual environment to git - add to git ignore

1.open powershell/terminal
2.navigate to your project
3.start your virtual environment - . tutorial-env/bin/activate
4.run your server - python3 manage.py runserver

ctrl c to stop server

cmd P to navigate through files
 
 migrations - instructions to the database

python3 manage.py migrate
(every time you make changes to the structure of your DB)

type - manage 
if you are unsure of the commands (there are a lot)

If ever changing models you must run:

python3 manage.py makemigrations polls (this creates)
python3 manage.py migrate (this applies them)
