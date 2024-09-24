# librenms-docker-compose

This docker-compose file will spin up a full network monitoring stack -- LibreNMS for SNMP Polling and Alerts, SyslogNG for Syslog messages, and SNMPtrapd for SNMP traps. Once container is running, you can configure LibreNMS via web interface (http://x.x.x.x:8000).

1. Clone this repo to your compose folder (I use /opt/docker/compose/$containername)
2. Create directories for your container volumes (I use /opt/docker/container/data/$containername)
3. Update .env, .msmptd.env, and .librenms.env files with your variables.
4. Update docker-compose.yml anywhere it says "CHANGEME" or "CHANGE-TO-DIRECTORY-YOU-WANT".
5. Run "docker-compose up -d" from the same directory that your yml file is in.
