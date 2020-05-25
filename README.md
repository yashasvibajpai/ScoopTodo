# ScoopTodo
### A simple to-do app, designed to implement the interconnected working of Django in backend, while React in frontend


After simple cloning, both django-server and react server need to be independently started on different ports.
To allow unification into a single port:
- CD into the frontend portion.
- Run
> npm install
- Run 
> npm run build
- Now your app will be ready with a production-level build.
- CD to the root directory of the cloned repo.
- Activate the virtual environment in /env .
- Execute
> python manage.py runserver
- Now the app will start on port 8000, the default port for django.
(Please configure the settings,py to suit your specific needs.)
