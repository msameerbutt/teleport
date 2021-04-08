## Steps
1. For (first time) installation
    1. Truncate `config` and `data` folders
    1. Execute `docker-compose -f docker-compose.firsttime.yml up -d`
    1. Above will populate `config` and `data` folders
    1. Shut down `docker-compose -f docker-compose.firsttime.yml down`
    1. Execute command to add test user `docker-compose exec teleport tctl users add testuser root,ubuntu`
1. For an existing installation
    1. Execute `docker-compose up -d`



# Resoruces
[Run Teleport using Docker](https://goteleport.com/docs/quickstart-docker/)
[Manage all your SSH servers with teleport](https://www.the-digital-life.com/ssh-teleport/)

