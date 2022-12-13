# instal Docker Compose on Amazon Linux
**The procedure to install docker compose on Amazon Linux is as follows:**

<sub>Note: To install [docker](https://github.com/saiunes/install-docker-Amazon-Linux/) follow instructions on [this page](https://github.com/saiunes/install-docker-Amazon-Linux/)</sub> 

<br/>

*Get the latest version docker-compose binary from GitHub*

```
sudo curl -L https://github.com/docker/compose/releases/latest/download/docker-compose-$(uname -s)-$(uname -m) -o /usr/local/bin/docker-compose
```

*Fix permissions after download*
```
sudo chmod +x /usr/local/bin/docker-compose
```

*Verify success:*

```
docker-compose version
```
