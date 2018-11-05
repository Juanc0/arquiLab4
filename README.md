# arquiLab4

# students
mvc -f pom.xml package
docker-compose build --force-rm
docker-compose up

# api-gateway
docker-compose build --force-rm
docker-compose up

# ldap
docker-compose build --force-rm
docker-compose up

# proxy
docker-compose build --force-rm
docker-compose up

small change
