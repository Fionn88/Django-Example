# dJango-example

## Introduction

This Project Is Practice DJango Framework

### Enviornment Setting

- Django Version
  - 3.2.19
- Python Version
  - 3.11.0
- CI Passed Python Version
  - 3.7、3.8、3.9、3.10、3.11

#### Installing virtualenv
```
py -m pip install --user virtualenv
```

#### Creating a virtual environment
```
py -m venv env
```

#### Activating a virtual environment
- Unix/macOS
```
source env/bin/activate
```
- Windows
```
.\env\Scripts\activate
```

#### Install Django
- Unix/macOS
```
python -m pip install Django
```
- Windows
```
py -m pip install Django
```


### Getting Started
- Create Project
```
django-admin startproject ProTwo
```

- Create App
```
python .\manage.py startapp AppTwo
```

- Migration
```
python manage.py migrate
```

- Run Server
```
python .\manage.py runserver
```

- Result
> Watching for file changes with StatReloader

> Performing system checks...

> System check identified no issues (0 silenced).

> June 16, 2023 - 09:11:15

> Django version 4.2.2, using settings 'ProTwo.settings'

> Starting development server at http://127.0.0.1:8000/

> Quit the server with CTRL-BREAK.

- You Can Connect The Service => http://127.0.0.1:8000
