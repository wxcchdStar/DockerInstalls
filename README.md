# DockerInstalls

## Jira（破解）

## Confluence（破解）

## SonarQube

## Jenkis

```
// docker是与宿主机共享的，但其他命令不行（例如：git、node、java、maven）
docker run -u root -d -p 30014:8080 -p 30016:50000 -v /home/docker/jenkins:/var/jenkins_home -v /var/run/docker.sock:/var/run/docker.sock jenkinsci/blueocean
```

## Rancher
```
docker run -d --restart=unless-stopped -p 30020:80 -p 30443:443 -v /home/docker/rancher:/var/lib/rancher rancher/rancher:latest --no-cacerts
```
