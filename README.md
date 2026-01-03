
1. pulling the docker repository: 

docker pull valeriansaliou/sonic:v1.4.9

2.create a config.cfg file in a created folder

-mkdir folder_name
-touch config.cfg

3. run docker

docker run -p 1491:1491 -v ./config.cfg:/etc/sonic.cfg -v ./store/:/var/lib/sonic/store/ valeriansaliou/sonic:v1.4.9

4. add a Dockerfile and run: docker build -t your_chosen_container_name . 

5. create img  

docker run -v ./store/:/var/lib/sonic/store/ your_chosen_container_name

```hello test```

6. 

docker run -p 1491:1491 -v ./store/:/var/lib/sonic/store/ maddox/sonic

7. add a name to container && let it work in background

docker run --name sonic -p 1491:1491 -v ./store/:/var/lib/sonic/store/ maddox/sonic -d

8. start the container: docker start name 


sdfsdfsdf