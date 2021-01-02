# Angular-Nginx-Express-Postgres
Boilerplate docker-compose with an Angular + Nginx frontend, an Express + Node backend and a Postgres database. 

Features a live development environment for angular frontend development and express backend development when running in dev mode.

To run:
```bash
chmod +x run.sh # if needed
./run.sh docker-compose.yml # To start production environment with nginx
./run.sh docker-compose.dev.yml # To start live development environment without nginx
```
### Prod

In your browser, navigate to localhost to view frontend and localhost:3000 to confirm backend is running correctly.

### Live Development Environment 

In your browser, navigate to localhost:4200 to view frontend and localhost:3000 to confirm backend is running correctly.