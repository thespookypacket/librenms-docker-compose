# librenms-docker-compose

1. Clone this repo to your compose folder (I use /opt/docker/compose/$containername)
2. Create directories for your container volumes (I use /opt/docker/container/data/$containername)
3. Update .env, .msmptd.env, and .librenms.env files with your variables.
4. Update docker-compose.yml anywhere it says "CHANGEME" or "CHANGE-TO-DIRECTORY-YOU-WANT".
5. Run "docker-compose up -d" from the same directory that your yml file is in.