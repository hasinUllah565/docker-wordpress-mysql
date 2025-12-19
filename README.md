## Docker WordPress + MySQL Project

This project uses Docker Compose to deploy WordPress with a MySQL database
in a multi-container environment.

WordPress and MySQL run as separate services and communicate using
environment variables and Docker networking. Docker volumes are used
to persist data.

After deploying the setup, I logged into the WordPress dashboard,
created a new user, and then accessed the MySQL container to verify
that the WordPress user data was stored in the MySQL database tables.
This confirms successful integration between WordPress and MySQL.

### How to Run
docker-compose up -d

Access the application at:
http://localhost:8000

