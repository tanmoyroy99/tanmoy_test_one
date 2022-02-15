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

docker container prune // to removed the untaged comment
 
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

 ### History
 docker history <contaner name>

 


