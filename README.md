# Basics

docker version `docker -v` to check docker compose compatibility

commands :

- lists images : `sudo docker image ls`
- lists container : `sudo docker ps`
- lists images :  `sudo docker image ls`
- Builds, (re)creates, starts, attaches a service : `sudo docker compose up -d`
- Stop and Remove container : `sudo docker compose down`
- remove images : `docker image rm {id}`
- remove container : `docker rm {id container}`
- lister les networks : `opoci_tools_opoci-network`
- run de conatiner : `docker run --name {nom de l'image} --rm`

connecting to the mysql server :

```bash
sudo docker compose exec database mysql -u {UserInDockerCompose} -p
```
