
Notes:
- The data is obtained from Google spreadsheets in the helpers/read_data_from_google_table.py file
- Folder with templates: subspace_dashboard/templates
- Design was based on ready bootstrap5 solutions (https://getbootstrap.com/docs/5.3/getting-started/introduction/)
- Fonts was taken from https://fontawesome.com/
- The site is located here https://www.pythonanywhere.com/

Commands:
create structure:
django-admin startproject subspace_dashboard
python manage.py startapp dashboard

create admin-user:
python manage.py createsuperuser

create db:
python manage.py makemigrations
python manage.py migrate

run:
python manage.py runserver