# Django_Ecommerce_Shop
## **STEPS to run the following project:**

1-->Download the zip file

2--> Extract anywhere you want to

3--> Now open cmd in the same directory where manage.py is present

4--> Now run the following commands

pip install-r requirements.txt

pip freeze  (to check whether all the required Python packages that are there in requirement.txt are installed or not)

python manage.py makemigrations  (it will create a migration file)

python manage.py migrate         (this will create database schemas/Modals required in our project )

python manage.py runserver       (python will start the Django project at localhost 8000)



## **for accessing the admin panel and creating a super user:**

run the following command:

python manage.py create superuser  (once you hit this command it will ask you for username, Email, and password once you have entered all this you are good to go with the admin panel)



