# # Docker_Demo: iknow-utils
The OEX package just uses a modest IRIS instance in Docker     
It merges IPM package of MDX2JSON with some demo data    
It is built using the small [Mini-Docker-Template](https://github.com/r-cemper/mini-docker) 
### Prerequisites   
Make sure you have [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and [Docker desktop](https://www.docker.com/products/docker-desktop) installed.    
### Installation    
Clone/git pull the repo into any local directory
```
$ git clone https://github.com/bdeboe/isc-iknow-utils.git 
```
Open the terminal in this directory and run:
```
$ docker-compose up -d
```
Test from docker console
```
$ docker-compose exec iris iris session iris
USER>
```
or using **WebTerminal**
```
http://localhost:42773/terminal/
```
### How to use it
This presents OEX package [iknow-utils](https://openexchange.intersystems.com/package/iknow-utils) using the actual IPM module    
All user documentation is found there in the [original repo](https://github.com/bdeboe/isc-iknow-utils/blob/main/README.md)  
