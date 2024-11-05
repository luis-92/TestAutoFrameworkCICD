# TestAutoFrameworkCICD
<img width="540" alt="image" src="https://github.com/user-attachments/assets/8077debe-1dbb-4acb-8958-33628a975efe">
<img width="599" alt="image" src="https://github.com/user-attachments/assets/55654c13-6603-4a1b-9485-3c7a1282fb4f">
<img width="585" alt="image" src="https://github.com/user-attachments/assets/e6e88b3c-f44c-4614-9cf4-3ede4014ab9f">
Each and every container in docker will have everythng that you need to run your applications
Docker can create Linux container or windows container
<img width="269" alt="image" src="https://github.com/user-attachments/assets/aa3044a8-87c9-4586-a6e8-803f69ea9589">


Terminologies                     DescriptionTerm                                   Similar java term


Dockerfile (has no extension)    Infrastructure as code                             java
Build                            creationing an image snapshot from docjerfile      compile / package
Image                            VM snaposhot                                       .class / .jar
Tag                               Version of image / release                        jar version
Container                        Light weigth VM created from a specific image      Instances / Objects  
                                  version we can create multimple containers
                                  with from same image              
Dockerhub                          Image Reposotory                                  Maven Repository

<img width="473" alt="image" src="https://github.com/user-attachments/assets/92bd39cc-9d08-47f3-ae25-216bf95f994c">

<img width="569" alt="image" src="https://github.com/user-attachments/assets/5c876c27-aa8e-4935-ab8c-732cc233c935">
we create with modulatity the docker containers
docker compose is the file in which you will provide the instructions to docker saying like "create these containers like this, put them in the network  etc"

Useful docker commands

Command                    Description

docker pull image         pulls an image from dockerhub
docker images             shows all the omages in our machine
docjker ps                shows all the running containers
docker ps-a               shows all the containers including the stopperd containers
docker stop container     stops a runnning container
id container name 
docker system prune -f   To remove all the stopped containers (docker do not touch the runnning containers)
docerk system prune -a   To remove all the stoppet containers (docker do not touch the running continers) + unused images
