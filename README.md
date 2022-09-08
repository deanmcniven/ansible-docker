# docker

Ansible role to install and configure docker

## Variables
* `docker_create_docker_conf` (optional): Create a docker.conf file; defaults to true
* `docker_dns_servers` (optional): list of dns servers for docker to query; defaults to 8.8.8.8
* `docker_dns_search` (optional): list of serch domains to configure for docker
