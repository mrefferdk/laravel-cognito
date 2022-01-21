### installation

- run composer install
- copy .env.example to .env and add relevant credentials
- run artisan key:generate  
- run s up -d
- run s artisan migrate


Current state:
- you can use /register to create a user (stores in AWS cognito as well as a dummy user in the local database)
- you can use /login to login using the Cognito user credentials
