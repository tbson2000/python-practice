# python-practice-making-django-webpage

### Please refer to the following guidelines on this url as I learn it from here:
[Get-Started-With-Django-1](https://realpython.com/get-started-with-django-1/)

## Djanggo Commands:
- For creating new app in Django
```bash
python manage.py startapp app_name # <-- *app_name* (highlighted)>
```
- For starting the Django server
```bash 
python manage.py runserver
```
- When there are changes to the DB model, need to run migration (whenever there are changes to the model/app/etc., need to run this):
```bash
python manage.py makemigration
```
- To apply the migration run the following so that Django will update the DB for you
```bash
pyhton manage.py migrate
```
- To work with Django admin, need to create a super user
```bash
python manage.py createsuperuser # --> need to remember the password
```