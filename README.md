# Plex

Plex based on the linuxserver.io container image https://hub.docker.com/r/linuxserver/plex

Pull repo

```git clone https://github.com/billsardine/plex-container.git```

Copy the .env.example file to .env

```cp .env.example .env```

Change the variables in the .env file to appropriate values

Start the container in the console to verify settings

```sudo sudo docker-compose up```

Kill the container and start it in the background

```sudo sudo docker-compose up -d```

