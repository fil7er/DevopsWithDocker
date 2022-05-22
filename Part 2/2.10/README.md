In my exercices i used a fully configured docker-compose.yml and dropped the Dockerfiles, but i'll redesign to make it work

reused Dockerfiles of 1.14:
    - removed all envs
changed docker-compose
    - removed working_dir
    - removed localhost ports
    - removed commands
    - add Dockerfiles and context in desired folders
    - docker commit the containers using Dockerfiles into frontend/backend images i don't know why this needed 