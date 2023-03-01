# Docker-Compose
Project with manifest YAML and schema definitions

```txt
git init
git add .
git commit -m "first commit"
git remote add origin https://github.com/canitanoa/Docker-Compose.git
git push -u origin main
```

### Prerequisits 

```txt
1. Install Docker Desktop
2. (Optional) ItelliJ 
    - Plugin: Docker -> To run the manifest with te IDe
3. Into the dirs there are the diferent manifest to be contenerized in Docker 
```
### Commands
```txt
- To RUN: 
    $ docker-compose -f manifest-example.yml up -d
- To VERIFY the containers:
    $ docker ps
- To STOP the container:
    $ docker stop name_container
```


