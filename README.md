"# tanmoy_test_one" 


### build Docker
docker build -t <Image Name> .

### build list images
docker images // all images
docker image ls  // all images in list

docker image prune  //  to removed untaged images
docker image rm <image ID/name> // to delete the image
docker image rm <image ID/name1> <image ID/name2> // to delete multiple image


### image tages
docker build -t <Image Name>:<tag name> .
docker image tag <Source Image Name>:<tag name>  <Des Image Name>:<tag name>

#### check the docker process
docker ps
#### check the docker process -a all
docker ps -a

docker container prune // to removed the untaged and stop contaner
 
 ### docker run
 docker run <contaner Name>

 ### docker run to overright the CMD
 docker run <contaner Name> npm start

 ### docker run in interactive mode
 docker run -it <contaner Name>

 ### docker run in interactive mode with shell
 docker run -it <contaner Name> sh

 docker run -d <contaner Name> //detached mode
 docker run -d --name <Name> <contaner Name> //detached mode

 //printenv -- for env view

 ## Docker Stop
 docker stop <container name>
 ## Docker Start
 docker stop <container name> //run commend use to run new image and start commend use for stop contaner

 ###Docker removed
 docker rm <contanerName>
 docker rm -f <contanerName> //for  force removed


 

 ### History
 docker history <contaner name>

### docker logs
docker logs <container ID>
docker logs -f <container ID> // to follow

## docker exec (to execatue the running container)
docker exec <containerName> <ANY COMMAND>
docker exec -it <containerName> sh // to open shell session

 


