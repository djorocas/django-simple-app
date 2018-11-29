# Django Simple App 

### Setup

 

### Create Virtual Environment (Virtualenv)

``` $ sudo apt-get -y install python-virtualenv ```
``` $ virtualenv . ```

### Activate Virtualenv 

``` $ source bin/activate ```

#### Clone Project

``` $ git clone git@github.com:djorocas/django-simple-app.git``` 

### Install Django in virtualenv

``` $ pip install -r requirements.txt ```

#### Run Migrations

```$ python manage.py migrate ```


#### Collect the static files

``` $ python manage.py collectstatic ```

#### Run project 

```$ python manage.py runserver 9000 ```

