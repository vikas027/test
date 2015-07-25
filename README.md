# Docker Container for running apache on CentOS 6.6
The docker container is based on CentOS 6.6. 
Apache v2.2.15 has been installed to support php v5.6

More details are available on [Docker Hub Registry - OwnCloud](https://registry.hub.docker.com/u/vikas027/centos6-apache2-php5.6/).
<br>
<br>
### Docker Installation
Install [Docker](https://docs.docker.com/installation/) on your favourite distro and run the container
<br>
<br>
### Run Container
Run the below commands to run the container

```bash
docker pull vikas027/centos6-apache2-php5.6

docker run --name <any_name> -d -p <host_http_port>:80 -p <host_https_port>:443 -v <path_of_website_files>:/var/www/html vikas027/centos6-apache2-php5.6
```
