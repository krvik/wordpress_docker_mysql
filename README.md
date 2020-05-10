# wordpress_docker_mysql
step1: install docker 
step2: Run docker-compose.yml file
    Always create a directory for docker-compose file
    command: #docker-compose up.
    -------it will launch the application.
    Go to browser: use address IP_Address:port  [here:1010]
    
 Things to consider while writing docker-compose file
 1. Since, its yaml file; avoid tab, instead use space.
 2. There should not be space between mountingVolume and mount point.
 3. mention version of keyword used in file; with the help of docker-compose documentation [ here 3 ]
 4. must use sudo, might give error if not used.
