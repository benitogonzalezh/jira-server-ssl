## Jira Server with SSL
Jira + Nginx + LetsEncrypt SSL</br>

This docker compose will setup everything to mount a jira sandbox over https and http.</br>
Tested on a droplet from digital ocean (8gb, 4vcpu, 160gb ssd, ubuntu).</br>Just install docker and docker compose on the instance and run the instructions.
You will need a domain to add the SSL certificate. You can use this free domains (https://www.freenom.com/)

## Instructions
1. Change the info on .env.local and rename the file to .env
2. Run `docker compose up`

This setup is only for testing purpose. If you want to run a production enviroment pls read the docs.
