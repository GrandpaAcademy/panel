## Pterodactyl Instalation

### Panel Dashboard
```bash
bash <(curl -s https://raw.githubusercontent.com/GrandpaAcademy/panel/refs/heads/main/panel.sh)
```

### Wings

```bash
sudo su
bash <(curl -s https://raw.githubusercontent.com/GrandpaAcademy/panel/refs/heads/main/wings.sh)
```

### Connect 

```bash
cd pterodactyl

sudo su

nano /etc/pterodactyl/config.yml

# Paste Your config

cd wings

docker-compose up -d --force-recreate

```
<b>OR</b> <br>
``use auto set command ``
