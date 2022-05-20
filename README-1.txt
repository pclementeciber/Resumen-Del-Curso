Maquinas Virtuales 
Vagant -> https://github.com/pclementeciber/repaso/blob/main/vagrant/vagrantfile

Docker
-->Manejo de los comandos
    --> DockerFile  -> https://docs.docker.com/engine/reference/builder/
            --> FROM , RUN , CMD , ADD , COPY .....
    --> Comandos de Docker 
            --> Run -> https://docs.docker.com/engine/reference/commandline/run/
            --> port -> https://docs.docker.com/engine/reference/commandline/port/
            --> ps -> https://docs.docker.com/engine/reference/commandline/ps/
            --> push -> https://docs.docker.com/engine/reference/commandline/push/
            --> pull -> https://docs.docker.com/engine/reference/commandline/pull/
            --> save -> https://docs.docker.com/engine/reference/commandline/save/
            --> stop -> https://docs.docker.com/engine/reference/commandline/stop/
            --> build -> https://docs.docker.com/engine/reference/commandline/build/ 
            --> rm -> https://docs.docker.com/engine/reference/commandline/rm/
            --> system prune -> https://docs.docker.com/engine/reference/commandline/system_prune/
            --> log -> https://docs.docker.com/engine/reference/commandline/logs/

    --> docker-compose
        --> -f docker-compose.yml   --> (estructura minima -> nombre , imagen , puertos,volumenes, network)
        --> Comandos interesantes 
        docker-compose XXXXXX -f docker-compose.yml -d ........
            --> build -> https://docs.docker.com/compose/reference/build/
            --> up VS create --> create esta deprecado -> https://docs.docker.com/compose/reference/up/
            --> rm -> https://docs.docker.com/compose/reference/rm/
            --> stop -> https://docs.docker.com/compose/reference/stop/
            --> logs -> https://docs.docker.com/compose/reference/logs/
            ....

--> Standalone -> https://docs.docker.com/engine/install/ubuntu/
--> Cluster -> https://docs.docker.com/engine/swarm/swarm-tutorial/create-swarm/
        --> Swarm -> como se crera un cluster (steps)
            --> infraestructura Tolerante 
                    --> A.A.
                    --> A.P.
you can consider the docker service vs docker stack is the same as docker run vs docker compose, but in the docker swarm cluster.

--> GIT --> Versionado --> IaaS PaaS *(Pendiente)
                            --> Ansible (Galaxy)
                            --> Terraform / Packer 

    -->branch -> para que -> DEV , TEST, UAT , Features ... Master
    --> fichero .gitignore 
    --> comandos
        --> push -> ejemplos
        --> pull -> ejemplos
        --> commit -> 
        --> add -> 
        --> checkout
        --> clone
        --> branch

    --> git submodule -> *Pendiente

Traefik *(Pendiente)
--> Load Balancer  /  Haproxy   

Registry --> Harbor *(Pendiente)
    -> Servicio dentro del cluster (docker) / servicio externo al cluster (dockerhub) / instalado como software en otra maquina de tu red
    -> Repositorio de Imagenes de Docker 
    -> Replicar las imagenes de docker en nuestro cluster de swarm    

--------------------------------------------------------
Jenkins -> https://github.com/pclementeciber/repaso/blob/main/Jenkins/
    --> Jobs
    --> JenkinsPipeline









