# Docker on Windows

How-to setup Docker on Windows 10

## Choco Install

```powershell
choco install docker-cli
choco install docker-desktop
```

## Docker Basics

- ![Docker Hub](https://hub.docker.com/)
- ![Docker CLI Reference](https://docs.docker.com/engine/reference/commandline/cli/) 

Launch an interactive docker container

```
docker run -t -i ubuntu bash
```

Install applications within container

```bash
sudo apt install ifconfig
```
