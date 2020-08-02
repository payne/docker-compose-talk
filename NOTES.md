# Pluaralsight Docker Web Dev. Class
## Agenda
1. Getting started with docker compose
2. docker-compose.yml file
   1. linking
   2. bridge networks
   2. ports external:internal
   3. volumes - Map to directories, files, or docker-compose managed
   3. startup order
3. docker compose commands
   1. Getting all logs at once
   1. view status of running containers
   1. docker-compose up -d
   1. docker-compose down -v
   1. docker-compose logs
   1. docker-compose logs -f application
   2. docker-compose restart application
   2. docker-compose down -v 
   2. docker-compose ps
   2. docker-compose stop
   3. docker-compose start
   3. docker-compose rm
   4. docker-compose build
   4. docker-compose application
4. docker compose in action
5. setting up development services 
6. Creating a custom docker-compose.yml file that allows for configuration
   1. e.g. environment variables
   1. `env_file` example:
   ```
   env_file:
     - ./app${APP_ENV}.env
   ```
7. Managing Development Services


# Neato demos
1. ElasticSearch docker-compose setup
2. SonarQube Docker-compose setup
3. Fava and Beancount with a WAF for authentication (or keycloak)
4. ssl termination with haproxy or ngninx (spelling)

# Looks like it might be IT
1. https://github.com/francoisruty/fruty_nginx-oauth
2. https://www.deskriders.dev/posts/005-protecting-applications-oauth2-proxy/

# Try https://oauth2-proxy.github.io/oauth2-proxy/
