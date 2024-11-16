# Learning_Docker

### Before Docker
1. Installation process different on each OS environment
2. If there are 10 services then there are many steps where something could go wrong

### With Docker
1. Own isolated environment
2. Packaged with all needed configurations
3. One same command to run on all OS environments
4. Can also run same app with 2 different versions of a service

### Docker Compose vs Dockerfile
- A Dockerfile is a simple text file that contains the commands a user could call to assemble an image.
- Docker Compose is a tool for defining and running multi-container Docker applications.Define the services that make up your app in docker-compose.yml so they can be run together in an isolated environment.Basically running multiple dockerfiles at once.
