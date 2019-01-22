ENV setup

yum install centos-release-scl
yum install rh-python36
scl enable rh-python36 bash

python --version

Python 3.6.3


Ref Doc

https://tutorial.djangogirls.org/en/


mkdir djangogirls
cd djangogirls/
virtualenv --python=python3.6 myvenv
source myvenv/bin/activate



django-admin startproject mysite .



python -m pip install --upgrade pip
pip install -r packege.txt


python manage.py runserver 0.0.0.0:8000
