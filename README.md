## Setup

Clone the project

```bash
git clone https://github.com/bksun/my-quora-app.git
```

create and start a a virtual environment

```bash
virtualenv env --no-site-packages

source env/bin/activate
```

Install the python package requirements using `pip`.

```bash
pip install -r requirements.txt
```

Run the migrate command to create database tables.

```bash
python manage.py migrate
```

Use the `createsuperuser` command to create a user who has superuser privileges.

```bash
python manage.py createsuperuser
```

Finally run the server using the `runserver` command.

```bash
python manage.py runserver
```
