# jenkins
jenkins data
ADD WEBHOOK 
url of app /github-webhook/






RUNNING ON CONTAINER
#JENKINS DOCKER INSTALL
sudo apt install docker.io -y
sudo apt install docker-compose -y [install docker compose]

docker --version

Create conbtainer in OUTPUT directory 
sudo docker build . -t mywebsiteimage [image creation]
sudo docker run -d --name (container name) -p 8000:8000 (image):latest [container creation]
sudo docker ps -a [cotainer check]
sudo docker stop (container name) [stop container]
sudo docker kill (container id) [kill container]
sudo docker rm (container id) [completely remove container]

FOR AUTOMATION
lsof -i:8000 
GO TO SERVER:
sudo usermod -aG docker jenkins
sudo systemctl restart docker [restart docker]
sudo systemctl restart jenkins [restart jenkins]

GO TO JENKINS > CONFIG > BUILD STEPS > EXECUTE SHELL
TYPE =
sudo docker build -t (img name) .
sudo docker run -d --name (container name) -p 8000:8000 (img name)



DOCKER COMPOSE 
EXECUTE SHELL
docker-compose down
docker-compose up -d
