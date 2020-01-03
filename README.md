# Getting Started
## Installtion:
1. First of install <b>[python3](https://www.python.org/downloads/)</b> ,if not installed.<br>
2. Then from terimnal (on linux) or cmd (on windows) install <b>[virtual envrionment](https://pypi.org/project/virtualenv/)</b>,if not installed.
```bash
$ python -m install virtualenv
```

### After installtion part:
Setup project environment with [virtualenv](https://virtualenv.pypa.io) and [pip](https://pip.pypa.io).

```bash
$ virtualenv project-env
$ source project-env/bin/activate
$ pip install -r requirements.txt


$ cd projectname/
$ python manage.py migrate
$ python manage.py runserver
```
