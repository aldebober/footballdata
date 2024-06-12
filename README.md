## Running Application

Docker container runs with command 'docker-compose up -d' from root folder where compose.yaml. 
The application and Dockerfile are located in app folder and structure is:

```
.
|-- README.md
|-- app
|   |-- Dockerfile
|   |-- README.md
|   |-- api.py
|   |-- main.py
|   |-- requirements.txt
|   `-- templates
|       `-- index.html
|-- compose.yaml
`-- nginx
    `-- default.conf
```

Requirements:
 - Docker
 - Docker compose script

Run docker:
```
docker-compose up -d
```
