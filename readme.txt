Service Discovery server
     Instead of manually keeping track of what microservices that are deployed currently and on what hosts and ports we need service discovery functionality that allows, through an API, microservices to self-register at startup.


需要有 docker env 才能用docker-maven-plugin

# eval $(docker-machine env)


 关于 Dockerfile


 镜像名有命名规则

 Invalid repository name ... only [a-z0-9-_.] are allowed


 查看deamon 日志
 docker-macher ssh

tail -f /var/log/docker.log 查看日志
