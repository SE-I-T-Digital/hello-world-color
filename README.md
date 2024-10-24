# hello-world-color

Docker compose for installation:
- Create .env file in the same directory of the docker-compose.yml file. see the .env file as example and replace it it with your .env file.

- Run with defaults env's: docker-compose up -d

For debugging inject variables via cli
- Run with override env's: DISPLAY_IMAGE=hello-world-2.png BACKGROUND_COLOR=lightgreen docker-compose up -d


Access the Application http://localhost:8080
- access port is a variable set in the .env file, if HOST_PORT changed in the .env, the access host port need to be changed accordingly.
