# django_skeleton
### Django Project Quickstart Skeleton

We suggest the file/directory sturcture for the Django project quickstart as follows:

```
project_folder\
    venv\
        Scripts\ (on Windows)
            activate.bat
        bin\ (on Linux)
            activate
            activate.csh
    repo\ (current project)
        project\
            manage.py
            conf\
                __init__.py
                settings.py
                urls.py
                wsgi.py
            app1\
            app2\
```

You have to create two folders `project_folder`, `venv` by yourself.

We prefer adding project init year month prefix such as "yyyymm_" (i.e. `201605_pythonstory`) to project_folder because it makes easier to manage several projects simaltaneously.

Each developer may have their own virtual environment directory `venv`.

This repository name is currently `django_skeleton`, but we propose to rename it to `repo`. Unity by convention helps us to manage projects a lot easier.

```
git clone https://github.com/pythonstory/django_skeleton repo
```
