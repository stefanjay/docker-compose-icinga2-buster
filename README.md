# docker-compose Icinga2 stack

### docker-compose version 3.6 running on debian buster

```
docker-ce                        5:20.10.5~3-0~debian-buster
docker-ce-cli                    5:20.10.5~3-0~debian-buster
docker-ce-rootless-extras        5:20.10.5~3-0~debian-buster
docker-compose                   1.21.0-3
```
docker-compose configuration to start-up an Icinga stack containing
Icinga 2, Icinga Web 2 and Icinga DB.

* Ensure you have the latest Docker and docker-compose versions and
then just run `docker-compose up -d` in order to start the Icinga stack from the ./repo-clone.

-OR-

* Run the command from any directory to start the icinga2 stack

Icinga Web is provided on { localhost:<port> } **8080** and you can access the Icinga 2 API on port **5665**.
The default user of Icinga Web is `icingaadmin` with password `icinga`.

---
##### fork from https://github.com/lippserd/docker-compose-icinga by Eric Lippmann | @lippserd 