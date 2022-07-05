# Multiple PostgreSQL Database Docker Compose

This docker compose configuration will create multiple databases and users instances on a single PostgreSQL server.

### How to Use

1. Clone this repository
2. Make sure that Docker Engine and Docker Compose is installed and running. You can download it at [https://www.docker.com/get-started/](https://www.docker.com/get-started/)
3. Copy `.env.sample` and rename it as `.env`
4. Update the environment variables as required
5. Run `docker compose up --build` 
6. Add and manage your PostgreSQL server with PGadmin at [http://localhost:1234/](http://localhost:1234/) (optional)


### License:  
See LICENSE file