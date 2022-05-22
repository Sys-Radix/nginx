This project needs an external docker network created by:

```sh
docker network create --driver bridge --subnet=10.5.0.0/16 --gateway=10.5.0.1 app_net
```
