# postgres-pgadmin-docker
 _This project demonstrates how to set up PostgreSQL and pgAdmin using Docker Compose._
## Prerequisites
> _[`Docker`](https://www.docker.com/get-started)_

### Getting Started
Clone this repository to your local machine:
```sh
git clone https://github.com/Rishikesh9919/postgres-pgadmin-docker.git
cd postgres-pgadmin-docker
```
Start the services by running the following command in the terminal:
```sh
docker compose -f .\compose.yaml up -d
```
Docker Compose will download the necessary images and start PostgreSQL and pgAdmin containers.

PostgreSQL and pgAdmin will now be running. You can access pgAdmin in your web browser at
```sh
http://localhost:7070
```
Log in using the following credentials:
- Email: pgadmin@mail.com
- Password: pgadmin@password

You can connect to the PostgreSQL database using the following connection details:
- Host: postgres
- Port: 5432
- Database: postgres
- Username: postgres
- Password: postgres@password

### Cleanup
To stop and remove the containers, run:
```sh
docker compose -f .\compose.yaml down
```
