# producthunt_project
It is a Django web app where a user can login and add a product and vote for his product as well as for other user's products.
In short, it is a product voting web application.

Installations required to get this app up and running:

1. Install Virtual environment and run it.
2. Install Django 2.2.* -----> Command: pip install django==2.2.*
3. Install psycopg2 -----> Command: pip install psycopg2
4. Install psycopg2-binary -----> Command: pip install psycopg2-binary
5. Install whitenoise 3.3.1. -----> Command: pip install whitenoise==3.3.1.
6. Install Pillow -----> Command: pip install pillow
7. Get postgres database installed and create a table named "producthuntdb"
8. Fire Migrate command -----> Command: python manage.py migrate 
9. Run the project -----> Command: python manage.py runserver
10. If you face any issue regarding the hunter/existing user then try to create your own superuser in django -----> Command: python manage.py createsuperuser

Now, login into the website and add your own products with the + sign present on the nav bar. Thereafter, you can also vote for your product as well as for other user's products.

Note: Since the project is for educational purpose only it has Secret Key present and debug=True.
