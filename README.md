# InterviewSchedule_DjangoProject

#### Python And Django Setup
Required Python Version: Python 3.10.X

1. Install required python packages  
    `pip install -r requirements.txt`
2. Create database migrations in django  
    `python manage.py makemigrations `
3. Write migration changes in database  
    `python manage.py migrate `        
4.  Create superuser  
    `python manage.py createsuperuser `
5.  Run Django server  
    `python manage.py runserver 0.0.0.0:8000 `



## Misc Python Notes
### How to run scripts with Django shell
1. Starting Django shell  
    `python manage.py shell 
2. Run an external script in the shell  
    `exec(open('scripts/filename.py').read())`
## How to delete all django database migration files
`find . -path "*/migrations/*.py" -not -name "__init__.py" -delete`  
`find . -path "*/migrations/*.pyc"  -delete` 
