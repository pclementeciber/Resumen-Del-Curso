Docker
-->Manejo de los comandos
    --> DockerFile
            --> FROM , RUN , CMD , ADD , COPY .....
    --> Comandos de Docker 
            --> Run -> opciones -> ejemplos
            --> port -> opciones -> ejemplos
            --> ps -> opciones -> ejemplos
            --> push -> opciones -> ejemplos
            --> pull -> opciones -> ejemplos
            --> save -> opciones -> ejemplos
            --> stop -> opciones -> ejemplos
            --> build -> opciones -> ejemplos 
            --> rm -> opciones -> ejemplos
            --> system prune -> ejemplos y para que!
            --> log -> opciones -> ejemplos
    --> docker-compose
        --> -f docker-compose.yml   --> (estructura minima -> nombre , imagen , puertos,volumenes, network)
        --> Comandos interesantes 
        docker-compose XXXXXX -f docker-compose.yml -d ........
            --> build
            --> up VS create --> diferencias y porque 
            --> rm
            --> stop
            --> logs 
            ....

--> Standalone
--> Cluster
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
Jenkins 
    --> Jobs
    --> JenkinsPipeline









