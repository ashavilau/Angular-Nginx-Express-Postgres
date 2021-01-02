# Angular-Nginx-Express-Postgres
Boilerplate docker-compose with an Angular + Nginx frontend, an Express + Node backend and a Postgres database

To run:
```bash
chmod +x run.sh # if needed
./run.sh docker-compose.yml # To start production environment with nginx
./run.sh docker-compose.dev.yml # To start development environment without nginx
```
### Prod

In your browser, navigate to localhost to view frontend and localhost:3000 to confirm backend is running correctly.

### Dev 

In your browser, navigate to localhost:4200 to view frontend and localhost:3000 to confirm backend is running correctly.