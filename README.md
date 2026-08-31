# SQL+Python (+MongoDB) Docker Environment
**Description**: Dockerfiles and docker compose for SQL and Python environment for STAT 624

**Optional** replace `docker-compose.yml` file with the docker compose file located in `docker-compose (+mongodb)` if you want to set up a MongoDB environment on your local machine. Note: This will add a Docker image of approximately 1.5 GB.

## Quick start guide
1. Download zipped folder containing all files in this repository.
2. Unzip folder and store in local directory of your choosing.
3. In a terminal window, navigate to the local directory containing `docker-compose.yml`.
4. Run the command `docker compose up`.  The Docker images will be downloaded to your system and containers will be created accordingly.

Check conditions:

5. Python:  Open a web browser window, copy and paste the custom URL provided in the terminal window to access the Jupyter notebook environment to interact with the database. 
6. PostgreSql:  Open a web browser window and type `localhost:5050` to open pgAdmin4 GUI to interact with the database.


** Use `docker ps` to list all running docker container

** Use `docker stop [container_name]` to stop unused docker container and save/free computing resources used by its processes

** -- Use Docker Desktop to manually stop/run a container
 
