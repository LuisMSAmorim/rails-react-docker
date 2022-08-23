## Techs

- Docker;
- Docker Compose;
- Ruby on Rails 7;
- React.JS (with TypeScript and Vite);
- PostGreSQL;

### Getting Started

- Clone this repo;
- Build the containers: ```sudo docker-compose build```
- Run the containers: ```sudo docker-compose up```
- Enter in backend container bash: ```sudo docker exec -it basiconfig_backend_1 /bin/bash```
- Create the database: ```rails db:create```
- Open "localhost:5000" and "localhost:5001"