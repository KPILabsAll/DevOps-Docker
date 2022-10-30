## Build image
```
docker build . -t vynnykv/node-app:latest
```
## Run container
```
docker run -p 80:80 -d --memory="50m" --cpus=2 vynnykv/node-app:latest
```
### Node app runs at 80 port