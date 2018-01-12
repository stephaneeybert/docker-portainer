Start the application in swarm mode
docker stack deploy --compose-file docker-compose-swarm.yml portainer

Stop the swarm application
docker stack rm portainer

Open the application
http://localhost:9005/#/dashboard
http://www.thalasoft.com:9005/#/dashboard

Log in with
User: stephane
Password: 40m...

The project
https://portainer.io
