# djangoPractice

Creating a polls app in python :) 

```
python3 manage.py startapp polls
```
This command creates the polls directory with all the relative files. 
```
python manage.py makemigrations polls
```

creates the polls migration

```
python manage.py sqlmigrate polls 0001
```
Allows us to see the sql commands within the migration. 

Remember the three-step guide to making model changes:
Change your models (in models.py).
- Run python manage.py makemigrations to create migrations for those changes
- Run python manage.py migrate to apply those changes to the database.

python3 manage.py shell - to access django equivalent of irb. 

