Steps to get started:
1. Clone this repo
2. Install Docker and Docker-Compose on local machine
3. Make sure pip is fully upgraded on local machine
4. Run pip install apache-airflow
5. Cd to the project root dir (where Dockerfile is located)
6. Run command: docker-compose up -d (-d runs in detached mode so you don't see the outputs, there will be some errors in outputs, but the webserver still runs ok)
7. Run command: docker-compose down to shut down all containers when you want to stop Airflow
8. Test that Airflow is running by visiting localhost:8080 on local machine (if it isn't running, make sure docker containers are ok with: docker ps command)