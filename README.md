	python3 -m venv ~/.virtualenvs/django-h5p-standalone

	source ~/.virtualenvs/django-h5p-standalone/bin/activate

	python3 -m pip install Django

	~/.virtualenvs/django-h5p-standalone/bin/django-admin startproject h5pdemo

	cd h5pdemo/

	pip install -r requirements.txt

	python manage.py migrate

	python manage.py runserver

