### Portainer

```sh
cd ./portainer
sudo docker-compose up -d
```

### Register

install dependencies

```sh
sudo apt install apache2-utils -y
```

generate auth credentials

```sh
cd ./register/auth
htpasswd -Bc registry.password registry-admin
```
