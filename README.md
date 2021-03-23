# Commento With Reverse-Proxy And Apache-PHP In Docker-Container

If docker-compose is not installed, installed it (on Debian-based distros)

`sudo apt-get install docker-compose`

Get This Repo

`git clone https://github.com/ramirezfx/commento-rev-proxy.git`

Navigate To The Working Directory:

`cd commento-rev-proxy`

Modify The Dockerfile To Fit Your Settings:

`sed -i 's/YOURDOMAIN/$YOURDOMAIN/g' docker-compose.yml`

where $YOURDOMAIN is YOUR Domain (ex.: mydomain.com)

create a folder name to your domain that holds the HTML-Files Of Your Website

`mkdir $YOURDOMAIN`

where $YOURDOMAIN is the domain of your website (ex. yourdomain.com)


Change the Values inside the file nginx.conf that suits to your domain

