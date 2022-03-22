Docker compose file to run postgres with pgadmin locally. Not suitable for production 


## Environment
All username, passwords are stores in the `db.env` file

## Run
> docker-compose up  

## Connect pgAdmin to postgress
1 - go to `localhost:5050`

2 - login with `PGADMIN_DEFAULT_EMAIL` and `PGADMIN_DEFAULT_PASSWORD` in 
`db.env` file

3 - Add new Server:
  - Hostname: postgres
  - Username: `POSTGRES_USER`
  - Password: `POSTGRES_PASSWORD`
