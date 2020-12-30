# Recipe app

# Docker:
- Run app: **docker-compose up**
- Run app with additional command: **docker-compose run app sh -c "command here"**
- Run tests: **docker-compose run app sh -c "python manage.py test"**
- Run tests with lint check: **docker-compose run app sh -c "python manage.py test && flake8"**