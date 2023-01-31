# Django_Ecommerce_Shop
## **STEPS to run following project:**

1-->Download the zip file

2-->extract anywhere you want to

3-->now open cmd in same directory where manae.py is present

4-->now run following commands

pip install-r requirements.txt

pip freeze  (to check wether all the recquired python packages that are there in requirement.txt are installed or not)

python manage.py makemigrations  (it will create a migration file)

python manage.py migrate         (this will create database schemas/Modals required in our project )

python manage.py runserver       (python will start django project at localhost 8000)



## **for accessing admin panel and creating super user:**

run the following command:

python manage.py create superuser  (once you hit this command it will ask you for usename, Email and password once you have entered all this you are good to go with the admin panel)



