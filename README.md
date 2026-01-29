# gitlab-deploy-lab

Lab personnel devops pour l'experimentation de mise en place d'une instance **GITLAB-SELF-HOSTED**.


docker exec -it gitlab-runner
gitlab-runner register  
--url http://gitlab-ce
--token glrt-MyPox_FQs8SCH5jvqGnvaG86MQp0OjEKdToxCw.01.121mpod01
--executor docker 
--docker-image alpine:latest
--docker-network-mode applications-networks