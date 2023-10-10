##To pull image from docker hub run this command

```
Dcoker pull <imagename-versionno.>
Docker pull Ubuntu ##If you do not specify version no. by default it will take the latest as a tag
Dcoker pull Ubuntu-latest
```

##To directly run a container (will also pull image from docker hub)

```
Dcoker Run <imagename-versionno.>
Docker run Ubuntu ##If you do not specify version no. by default it will take the latest as a tag
Dcoker run Ubuntu-latest
```
##To give a specific name to a conatiner use --name parameter
```
Dcoker Run --name <name you wants to give to your conatiner> <imagename-versionno.>
```
##To run a container in detached mode (running in background), use -d as a param

```
Dcoker Run -d <imagename-versionno.>
Docker run -d Ubuntu 
```

##To map/publish the ports use -p parameter and specify the ports
```
Dcoker Run -d -p <port which you want to access from host or browser:image port no.> <image name-version no.>
```
##To get list of all running container
```
Docker ps
```
##To Stop & remove the running container
```
Docker stop <container id>
Docker rm <container id>
```
