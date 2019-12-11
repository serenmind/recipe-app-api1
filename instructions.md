TDD - test drive development
	-write a code to be tested
	-write a testcase tests.py
	- $ docker-compose run app sh -c "python manage.py test && flake8"

delete both files after testing in order to integrate TDD on core app.

$ docker-compose run app sh -c "python manage.py startapp core"