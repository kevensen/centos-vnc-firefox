# centos-vnc-firefox
This actually will run Firefox inside a docker.io/kevensen/centos-vnc based image.

## To Run
```
docker run -d -p 5901:5901 --link vnc --name xrdp docker.io/kevensen/centos-vnc-firefox
```
