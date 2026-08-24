Configuration Steps
1.	Create a user (test1)
2.	Clone the Git repo
3.	Check the server resources
4.	Install the required packaged (docker)
5.	Allow the firewall port
6.	Docker is active and running
7.	Check the open ports
Containerization
1.	Install the docker
2.	Check the docker service working or not using hello-world image
3.	Write the Dockerfile 
4.	Write the docker-compose.yaml file
5.	Compose and build the docker image using “docker compose up -d --build” command
6.	Check both app and db image health and status using the “docker compose ps”
7.	Check the image owner using the “docker exec nextjs_app whoami” command
8.	Check the volume availability using the “docker volume ls | grep db_data” command



       Nginx Reverse Proxy & Domain Setup
1.	Point the dns name (dimudash.duckdns.org) to the server public IP (47.128.237.73)
2.	Write the nginx default.conf file 
3.	Validate the config by “nginx -t” command and it pass
4.	The nginx run on the container. So can’t reload the nginx in locally
5.	The 3 containers were up and run healthy for a while
6.	The application up and running successfully

GitHub Actions CI/CD
1.	Triger the workfloor to main branch
