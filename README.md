# recipe-app-api
Recipe API project

# To run the project
First, start docker  
Then run:
`docker-compose up -d`

# To run the test
First, start docker  
Then run:
`docker-compose run --rm app sh -c "python manage.py test"`

# To run flake8
First, start docker  
Then run:
`docker-compose run --rm app sh -c "flake8"`

# To create superuser account
First, start docker  
Then run:  
`docker-compose run --rum app sh -c "python manage.py createsuperuser"`
superuser@example.com/123456a@