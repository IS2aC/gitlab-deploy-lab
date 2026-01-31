# gitlab-deploy-lab

Lab personnel devops pour l'experimentation de mise en place d'une instance **GITLAB-SELF-HOSTED**.

Il convient avant tout deploiement de comprendre que  : 
<pre> 
Gitlab et Gitlab-runner sont deux composant differents qui doivent naturellement communiqué ensemble.
</pre>

## gitlab-selfdeploy-on-docker






docker exec -it gitlab-runner
gitlab-runner register  
--url http://gitlab-ce
--token glrt-MyPox_FQs8SCH5jvqGnvaG86MQp0OjEKdToxCw.01.121mpod01
--executor docker 
--docker-image alpine:latest
--docker-network-mode applications-networks